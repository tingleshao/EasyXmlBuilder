EasyXMLBuilder is an XML Builder written in ruby. 

It currently supports: 

- add a node by name
- add a node by EzXmlNodeObject

How to use:

In your ruby code, add load 'easyXMLBuilder.rb'

initialize EzXmlBuilder class:

	builder = EzXmlBuilder.new()

add node: 

	builder.addNode("nodename", "nodeContent")

or add a node with child node:

	node = EzXmlNode.new("nodename", "content")
	node.addChildNode("childNodename", "content")

	builder.addNode(node)

for suggestions and questions, send email to cshao@cs.unc.edu


TODO: 

      add delete node function
      add change node function

      In EzXmlNode class, add similiar functions.
      Let EzXmlNode class support "add Childnode by node" function.
	
      add XmlAnalyzer tool


---- 10/03/2012 ---- 
 