---
title: XPathNavigator
second_title: Referencia de la API de Aspose.Slides para C++
description: Proporciona un modelo de cursor para navegar y editar datos XML.
type: docs
weight: 66
url: /es/system.xml.xpath/xpathnavigator/
---
## XPathNavigator clase

Proporciona un modelo de cursor para navegar y editar datos XML.

```cpp
class XPathNavigator : public System::Xml::XPath::XPathItem,
                       public System::Xml::XPath::IXPathNavigable,
                       public System::Xml::IXmlNamespaceResolver
```

## Métodos

| Método | Descripción |
| --- | --- |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../../system.xml/xmlwriter/)\> [AppendChild](./appendchild/)() | Devuelve un objeto [XmlWriter](../../system.xml/xmlwriter/) utilizado para crear uno o más nodos hijos nuevos al final de la lista de nodos hijos del nodo actual. |
| virtual void [AppendChild](./appendchild/)([String](../../system/string/)) | Crea un nuevo nodo hijo al final de la lista de nodos hijos del nodo actual usando la cadena de datos XML especificada. |
| virtual void [AppendChild](./appendchild/)([SharedPtr](../../system/sharedptr/)\<[XmlReader](../../system.xml/xmlreader/)\>) | Crea un nuevo nodo hijo al final de la lista de nodos hijos del nodo actual usando el contenido XML del objeto [XmlReader](../../system.xml/xmlreader/) especificado. |
| virtual void [AppendChild](./appendchild/)([SharedPtr](../../system/sharedptr/)\<[XPathNavigator](./)\>) | Crea un nuevo nodo hijo al final de la lista de nodos hijos del nodo actual usando los nodos en el [XPathNavigator](./) especificado. |
| virtual void [AppendChildElement](./appendchildelement/)([String](../../system/string/), [String](../../system/string/), [String](../../system/string/), [String](../../system/string/)) | Crea un nuevo nodo elemento hijo al final de la lista de nodos hijos del nodo actual usando el prefijo de espacio de nombres, el nombre local y el URI del espacio de nombres especificados con el valor indicado. |
| virtual **bool** [CheckValidity](./checkvalidity/)([SharedPtr](../../system/sharedptr/)\<[System::Xml::Schema::XmlSchemaSet](../../system.xml.schema/xmlschemaset/)\>, [System::Xml::Schema::ValidationEventHandler](../../system.xml.schema/validationeventhandler/)) | Verifica que los datos XML en [XPathNavigator](./) cumplan con el esquema del lenguaje de definición XML [Schema](../../system.xml.schema/) (XSD) proporcionado. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XPathNavigator](./)\> [Clone](./clone/)() | Cuando se sobrescribe en una clase derivada, crea un nuevo [XPathNavigator](./) posicionado en el mismo nodo que este [XPathNavigator](./). |
| virtual [XmlNodeOrder](../../system.xml/xmlnodeorder/) [ComparePosition](./compareposition/)([SharedPtr](../../system/sharedptr/)\<[XPathNavigator](./)\>) | Compara la posición del [XPathNavigator](./) actual con la posición del [XPathNavigator](./) especificado. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XPathExpression](../xpathexpression/)\> [Compile](./compile/)([String](../../system/string/)) | Compila una cadena que representa una expresión [XPath](../) y devuelve un objeto [XPathExpression](../xpathexpression/). |
| virtual void [CreateAttribute](./createattribute/)([String](../../system/string/), [String](../../system/string/), [String](../../system/string/), [String](../../system/string/)) | Crea un nodo atributo en el nodo elemento actual usando el prefijo de espacio de nombres, el nombre local y el URI del espacio de nombres especificados con el valor indicado. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../../system.xml/xmlwriter/)\> [CreateAttributes](./createattributes/)() | Devuelve un objeto [XmlWriter](../../system.xml/xmlwriter/) utilizado para crear nuevos atributos en el elemento actual. |
| [SharedPtr](../../system/sharedptr/)\<[XPathNavigator](./)\> [CreateNavigator](./createnavigator/)() override | Devuelve una copia del [XPathNavigator](./). |
| virtual void [DeleteRange](./deleterange/)([SharedPtr](../../system/sharedptr/)\<[XPathNavigator](./)\>) | Elimina un rango de nodos hermanos desde el nodo actual hasta el nodo especificado. |
| virtual void [DeleteSelf](./deleteself/)() | Elimina el nodo actual y sus nodos hijos. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Compara objetos usando la semántica [Object.Equals](../../system/object/equals/) de C#. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compara objetos de tipo referencia al estilo de C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compara objetos de tipo valor al estilo de C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emula la comparación de punto flotante al estilo C# donde dos NaN se consideran iguales aunque según IEC 60559:1989 NaN no es igual a ningún valor, incluido NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emula la comparación de punto flotante al estilo C# donde dos NaN se consideran iguales aunque según IEC 60559:1989 NaN no es igual a ningún valor, incluido NaN. |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [Evaluate](./evaluate/)([String](../../system/string/)) | Evalúa la expresión [XPath](../) especificada y devuelve el resultado tipado. |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [Evaluate](./evaluate/)([String](../../system/string/), [SharedPtr](../../system/sharedptr/)\<[IXmlNamespaceResolver](../../system.xml/ixmlnamespaceresolver/)\>) | Evalúa la expresión [XPath](../) especificada y devuelve el resultado tipado, usando el objeto [IXmlNamespaceResolver](../../system.xml/ixmlnamespaceresolver/) especificado para resolver los prefijos de espacio de nombres en la expresión [XPath](../). |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [Evaluate](./evaluate/)([SharedPtr](../../system/sharedptr/)\<[XPathExpression](../xpathexpression/)\>) | Evalúa el [XPathExpression](../xpathexpression/) y devuelve el resultado tipado. |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [Evaluate](./evaluate/)([SharedPtr](../../system/sharedptr/)\<[XPathExpression](../xpathexpression/)\>, [SharedPtr](../../system/sharedptr/)\<[XPathNodeIterator](../xpathnodeiterator/)\>) | Utiliza el contexto suministrado para evaluar el [XPathExpression](../xpathexpression/) y devuelve el resultado tipado. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Solo para uso interno. |
| virtual [String](../../system/string/) [get_BaseURI](./get_baseuri/)() | Cuando se sobrescribe en una clase derivada, obtiene el URI base del nodo actual. |
| virtual **bool** [get_CanEdit](./get_canedit/)() | Devuelve un valor que indica si [XPathNavigator](./) puede editar los datos XML subyacentes. |
| virtual **bool** [get_HasAttributes](./get_hasattributes/)() | Devuelve un valor que indica si el nodo actual tiene atributos. |
| virtual **bool** [get_HasChildren](./get_haschildren/)() | Devuelve un valor que indica si el nodo actual tiene nodos hijos. |
| virtual [String](../../system/string/) [get_InnerXml](./get_innerxml/)() | Devuelve el marcado que representa los nodos hijos del nodo actual. |
| virtual **bool** [get_IsEmptyElement](./get_isemptyelement/)() | Cuando se sobrescribe en una clase derivada, obtiene un valor que indica si el nodo actual es un elemento vacío sin etiqueta de cierre. |
| **bool** [get_IsNode](./get_isnode/)() override | Devuelve un valor que indica si el nodo actual representa un nodo [XPath](../). |
| virtual [String](../../system/string/) [get_LocalName](./get_localname/)() | Cuando se sobrescribe en una clase derivada, obtiene el [XPathNavigator::get_Name](./get_name/) del nodo actual sin ningún prefijo de espacio de nombres. |
| virtual [String](../../system/string/) [get_Name](./get_name/)() | Cuando se sobrescribe en una clase derivada, obtiene el nombre calificado del nodo actual. |
| virtual [String](../../system/string/) [get_NamespaceURI](./get_namespaceuri/)() | Cuando se sobrescribe en una clase derivada, obtiene el URI del espacio de nombres del nodo actual. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlNameTable](../../system.xml/xmlnametable/)\> [get_NameTable](./get_nametable/)() | Cuando se sobrescribe en una clase derivada, obtiene el [XmlNameTable](../../system.xml/xmlnametable/) del [XPathNavigator](./). |
| static [SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IEqualityComparer](../../system.collections.generic/iequalitycomparer/)\<[SharedPtr](../../system/sharedptr/)\<[XPathNavigator](./)\>\>\> [get_NavigatorComparer](./get_navigatorcomparer/)() | Devuelve un [Collections::IEqualityComparer](../../system.collections/iequalitycomparer/) utilizado para la comparación de igualdad de objetos [XPathNavigator](./). |
| virtual [XPathNodeType](../xpathnodetype/) [get_NodeType](./get_nodetype/)() | Cuando se sobrescribe en una clase derivada, obtiene el XPathNodeType del nodo actual. |
| virtual [String](../../system/string/) [get_OuterXml](./get_outerxml/)() | Devuelve el marcado que representa las etiquetas de apertura y cierre del nodo actual y sus nodos hijos. |
| virtual [String](../../system/string/) [get_Prefix](./get_prefix/)() | Cuando se sobrescribe en una clase derivada, obtiene el prefijo de espacio de nombres asociado al nodo actual. |
| virtual [SharedPtr](../../system/sharedptr/)\<[System::Xml::Schema::IXmlSchemaInfo](../../system.xml.schema/ixmlschemainfo/)\> [get_SchemaInfo](./get_schemainfo/)() | Devuelve la información del esquema que se ha asignado al nodo actual como resultado de la validación del esquema. |
| [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [get_TypedValue](./get_typedvalue/)() override | Devuelve el nodo actual como un objeto empaquetado del tipo más apropiado. |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [get_UnderlyingObject](./get_underlyingobject/)() | Utilizado por implementaciones [XPathNavigator](./) que proporcionan una vista XML "virtualizada" sobre un almacén, para proporcionar acceso a los objetos subyacentes. |
| virtual [String](../../system/string/) [get_Value](../xpathitem/get_value/)() | Cuando se sobrescribe en una clase derivada, obtiene el valor **string** del elemento. |
| **bool** [get_ValueAsBoolean](./get_valueasboolean/)() override | Devuelve el valor del nodo actual como un [Boolean](../../system/boolean/). |
| [DateTime](../../system/datetime/) [get_ValueAsDateTime](./get_valueasdatetime/)() override | Devuelve el valor del nodo actual como un [DateTime](../../system/datetime/). |
| **double** [get_ValueAsDouble](./get_valueasdouble/)() override | Devuelve el valor del nodo actual como un [Double](../../system/double/). |
| **int32_t** [get_ValueAsInt](./get_valueasint/)() override | Devuelve el valor del nodo actual como un [Int32](../../system/int32/). |
| **int64_t** [get_ValueAsLong](./get_valueaslong/)() override | Devuelve el valor del nodo actual como un [Int64](../../system/int64/). |
| [TypeInfo](../../system/typeinfo/) [get_ValueType](./get_valuetype/)() override | Devuelve el tipo del nodo actual. |
| virtual [String](../../system/string/) [get_XmlLang](./get_xmllang/)() | Devuelve el ámbito **xml:lang** para el nodo actual. |
| [SharedPtr](../../system/sharedptr/)\<[System::Xml::Schema::XmlSchemaType](../../system.xml.schema/xmlschematype/)\> [get_XmlType](./get_xmltype/)() override | Devuelve la información XmlSchemaType del nodo actual. |
| virtual [String](../../system/string/) [GetAttribute](./getattribute/)([String](../../system/string/), [String](../../system/string/)) | Devuelve el valor del atributo con el nombre local y el URI de espacio de nombres especificados. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Obtiene la estructura de datos del contador de referencias asociada al objeto. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Análogo del método [Object.GetHashCode()](../../system/object/gethashcode/) de C#. Permite el hash de objetos personalizados. |
| virtual [String](../../system/string/) [GetNamespace](./getnamespace/)([String](../../system/string/)) | Devuelve el valor del nodo de espacio de nombres correspondiente al nombre local especificado. |
| [SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IDictionary](../../system.collections.generic/idictionary/)\<[String](../../system/string/), [String](../../system/string/)\>\> [GetNamespacesInScope](./getnamespacesinscope/)([XmlNamespaceScope](../../system.xml/xmlnamespacescope/)) override | Devuelve los espacios de nombres en alcance del nodo actual. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Obtiene el tipo real del objeto. Análogo a la llamada [System.Object.GetType()](../../system/object/gettype/) de C#. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../../system.xml/xmlwriter/)\> [InsertAfter](./insertafter/)() | Devuelve un objeto [XmlWriter](../../system.xml/xmlwriter/) utilizado para crear un nuevo nodo hermano después del nodo seleccionado actualmente. |
| virtual void [InsertAfter](./insertafter/)([String](../../system/string/)) | Crea un nuevo nodo hermano después del nodo seleccionado actualmente usando la cadena XML especificada. |
| virtual void [InsertAfter](./insertafter/)([SharedPtr](../../system/sharedptr/)\<[XmlReader](../../system.xml/xmlreader/)\>) | Crea un nuevo nodo hermano después del nodo seleccionado actualmente usando el contenido XML del objeto [XmlReader](../../system.xml/xmlreader/) especificado. |
| virtual void [InsertAfter](./insertafter/)([SharedPtr](../../system/sharedptr/)\<[XPathNavigator](./)\>) | Crea un nuevo nodo hermano después del nodo seleccionado actualmente usando los nodos del objeto [XPathNavigator](./) especificado. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../../system.xml/xmlwriter/)\> [InsertBefore](./insertbefore/)() | Devuelve un objeto [XmlWriter](../../system.xml/xmlwriter/) utilizado para crear un nuevo nodo hermano antes del nodo seleccionado actualmente. |
| virtual void [InsertBefore](./insertbefore/)([String](../../system/string/)) | Crea un nuevo nodo hermano antes del nodo seleccionado actualmente usando la cadena XML especificada. |
| virtual void [InsertBefore](./insertbefore/)([SharedPtr](../../system/sharedptr/)\<[XmlReader](../../system.xml/xmlreader/)\>) | Crea un nuevo nodo hermano antes del nodo seleccionado actualmente usando el contenido XML del objeto [XmlReader](../../system.xml/xmlreader/) especificado. |
| virtual void [InsertBefore](./insertbefore/)([SharedPtr](../../system/sharedptr/)\<[XPathNavigator](./)\>) | Crea un nuevo nodo hermano antes del nodo seleccionado actualmente usando los nodos en el [XPathNavigator](./) especificado. |
| virtual void [InsertElementAfter](./insertelementafter/)([String](../../system/string/), [String](../../system/string/), [String](../../system/string/), [String](../../system/string/)) | Crea un nuevo elemento hermano después del nodo actual usando el prefijo de espacio de nombres, el nombre local y el URI del espacio de nombres especificados, con el valor indicado. |
| virtual void [InsertElementBefore](./insertelementbefore/)([String](../../system/string/), [String](../../system/string/), [String](../../system/string/), [String](../../system/string/)) | Crea un nuevo elemento hermano antes del nodo actual usando el prefijo de espacio de nombres, el nombre local y el URI del espacio de nombres especificados, con el valor indicado. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Comprueba si el objeto representa una instancia del tipo descrito por targetType. Análogo al operador 'is' de C#. |
| virtual **bool** [IsDescendant](./isdescendant/)([SharedPtr](../../system/sharedptr/)\<[XPathNavigator](./)\>) | Determina si el [XPathNavigator](./) especificado es descendiente del [XPathNavigator](./) actual. |
| virtual **bool** [IsSamePosition](./issameposition/)([SharedPtr](../../system/sharedptr/)\<[XPathNavigator](./)\>) | Cuando se sobrescribe en una clase derivada, determina si el [XPathNavigator](./) actual está en la misma posición que el [XPathNavigator](./) especificado. |
| void [Lock](../../system/object/lock/)() | Implementa el bloqueo de la sentencia C# lock(). Llamar directamente o usar el objeto centinela [LockContext](../../system/lockcontext/). |
| [String](../../system/string/) [LookupNamespace](./lookupnamespace/)(const [String](../../system/string/)\&) override | Devuelve el URI del espacio de nombres para el prefijo especificado. |
| [String](../../system/string/) [LookupPrefix](./lookupprefix/)(const [String](../../system/string/)\&) override | Devuelve el prefijo declarado para el URI del espacio de nombres especificado. |
| virtual **bool** [Matches](./matches/)([SharedPtr](../../system/sharedptr/)\<[XPathExpression](../xpathexpression/)\>) | Determina si el nodo actual coincide con el [XPathExpression](../xpathexpression/) especificado. |
| virtual **bool** [Matches](./matches/)([String](../../system/string/)) | Determina si el nodo actual coincide con la expresión [XPath](../) especificada. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Análogo al método [Object.MemberwiseClone()](../../system/object/memberwiseclone/) de C#. Permite clonar tipos personalizados. |
| virtual **bool** [MoveTo](./moveto/)([SharedPtr](../../system/sharedptr/)\<[XPathNavigator](./)\>) | Cuando se sobrescribe en una clase derivada, mueve el [XPathNavigator](./) a la misma posición que el [XPathNavigator](./) especificado. |
| virtual **bool** [MoveToAttribute](./movetoattribute/)([String](../../system/string/), [String](../../system/string/)) | Mueve el [XPathNavigator](./) al atributo con el nombre local y el URI de espacio de nombres coincidentes. |
| virtual **bool** [MoveToChild](./movetochild/)([String](../../system/string/), [String](../../system/string/)) | Mueve el [XPathNavigator](./) al nodo hijo con el nombre local y el URI de espacio de nombres especificados. |
| virtual **bool** [MoveToChild](./movetochild/)([XPathNodeType](../xpathnodetype/)) | Mueve el [XPathNavigator](./) al nodo hijo del XPathNodeType especificado. |
| virtual **bool** [MoveToFirst](./movetofirst/)() | Mueve el [XPathNavigator](./) al primer nodo hermano del nodo actual. |
| virtual **bool** [MoveToFirstAttribute](./movetofirstattribute/)() | Cuando se sobrescribe en una clase derivada, mueve el [XPathNavigator](./) al primer atributo del nodo actual. |
| virtual **bool** [MoveToFirstChild](./movetofirstchild/)() | Cuando se sobrescribe en una clase derivada, mueve el [XPathNavigator](./) al primer nodo hijo del nodo actual. |
| virtual **bool** [MoveToFirstNamespace](./movetofirstnamespace/)([XPathNamespaceScope](../xpathnamespacescope/)) | Cuando se sobrescribe en una clase derivada, mueve el [XPathNavigator](./) al primer nodo de espacio de nombres que coincida con el XPathNamespaceScope especificado. |
| **bool** [MoveToFirstNamespace](./movetofirstnamespace/)() | Mueve el [XPathNavigator](./) al primer nodo de espacio de nombres del nodo actual. |
| virtual **bool** [MoveToFollowing](./movetofollowing/)([String](../../system/string/), [String](../../system/string/)) | Mueve el [XPathNavigator](./) al elemento con el nombre local y el URI de espacio de nombres especificados en orden de documento. |
| virtual **bool** [MoveToFollowing](./movetofollowing/)([String](../../system/string/), [String](../../system/string/), [SharedPtr](../../system/sharedptr/)\<[XPathNavigator](./)\>) | Mueve el [XPathNavigator](./) al elemento con el nombre local y el URI de espacio de nombres especificados, al límite especificado, en orden de documento. |
| virtual **bool** [MoveToFollowing](./movetofollowing/)([XPathNodeType](../xpathnodetype/)) | Mueve el [XPathNavigator](./) al siguiente elemento del XPathNodeType especificado en orden de documento. |
| virtual **bool** [MoveToFollowing](./movetofollowing/)([XPathNodeType](../xpathnodetype/), [SharedPtr](../../system/sharedptr/)\<[XPathNavigator](./)\>) | Mueve el [XPathNavigator](./) al siguiente elemento del XPathNodeType especificado, al límite especificado, en orden de documento. |
| virtual **bool** [MoveToId](./movetoid/)([String](../../system/string/)) | Cuando se sobrescribe en una clase derivada, se mueve al nodo que tiene un atributo de tipo **ID** cuyo valor coincide con el [String](../../system/string/) especificado. |
| virtual **bool** [MoveToNamespace](./movetonamespace/)([String](../../system/string/)) | Mueve el [XPathNavigator](./) al nodo de espacio de nombres con el prefijo de espacio de nombres especificado. |
| virtual **bool** [MoveToNext](./movetonext/)() | Cuando se sobrescribe en una clase derivada, mueve el [XPathNavigator](./) al siguiente nodo hermano del nodo actual. |
| virtual **bool** [MoveToNext](./movetonext/)([String](../../system/string/), [String](../../system/string/)) | Mueve el [XPathNavigator](./) al siguiente nodo hermano con el nombre local y el URI de espacio de nombres especificados. |
| virtual **bool** [MoveToNext](./movetonext/)([XPathNodeType](../xpathnodetype/)) | Mueve el [XPathNavigator](./) al siguiente nodo hermano del nodo actual que coincide con el XPathNodeType especificado. |
| virtual **bool** [MoveToNextAttribute](./movetonextattribute/)() | Cuando se sobrescribe en una clase derivada, mueve el [XPathNavigator](./) al siguiente atributo. |
| virtual **bool** [MoveToNextNamespace](./movetonextnamespace/)([XPathNamespaceScope](../xpathnamespacescope/)) | Cuando se sobrescribe en una clase derivada, mueve el [XPathNavigator](./) al siguiente nodo de espacio de nombres que coincide con el XPathNamespaceScope especificado. |
| **bool** [MoveToNextNamespace](./movetonextnamespace/)() | Mueve el [XPathNavigator](./) al siguiente nodo de espacio de nombres. |
| virtual **bool** [MoveToParent](./movetoparent/)() | Cuando se sobrescribe en una clase derivada, mueve el [XPathNavigator](./) al nodo padre del nodo actual. |
| virtual **bool** [MoveToPrevious](./movetoprevious/)() | Cuando se sobrescribe en una clase derivada, mueve el [XPathNavigator](./) al nodo hermano anterior del nodo actual. |
| virtual void [MoveToRoot](./movetoroot/)() | Mueve el [XPathNavigator](./) al nodo raíz al que pertenece el nodo actual. |
|  [Object](../../system/object/object/)() | Crea el objeto. Inicializa todas las estructuras de datos internas. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Constructor de copia. Realmente no copia nada, solo inicializa un nuevo objeto y permite la construcción por copia de subclases. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operador de asignación. Realmente no copia nada, solo inicializa un nuevo objeto y permite la construcción por copia de subclases. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../../system.xml/xmlwriter/)\> [PrependChild](./prependchild/)() | Devuelve un objeto [XmlWriter](../../system.xml/xmlwriter/) usado para crear un nuevo nodo hijo al principio de la lista de nodos hijos del nodo actual. |
| virtual void [PrependChild](./prependchild/)([String](../../system/string/)) | Crea un nuevo nodo hijo al principio de la lista de nodos hijos del nodo actual usando la cadena XML especificada. |
| virtual void [PrependChild](./prependchild/)([SharedPtr](../../system/sharedptr/)\<[XmlReader](../../system.xml/xmlreader/)\>) | Crea un nuevo nodo hijo al principio de la lista de nodos hijos del nodo actual usando el contenido XML del objeto [XmlReader](../../system.xml/xmlreader/) especificado. |
| virtual void [PrependChild](./prependchild/)([SharedPtr](../../system/sharedptr/)\<[XPathNavigator](./)\>) | Crea un nuevo nodo hijo al principio de la lista de nodos hijos del nodo actual usando los nodos del objeto [XPathNavigator](./) especificado. |
| virtual void [PrependChildElement](./prependchildelement/)([String](../../system/string/), [String](../../system/string/), [String](../../system/string/), [String](../../system/string/)) | Crea un nuevo elemento hijo al principio de la lista de nodos hijos del nodo actual usando el prefijo de espacio de nombres, el nombre local y el URI de espacio de nombres especificados con el valor especificado. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlReader](../../system.xml/xmlreader/)\> [ReadSubtree](./readsubtree/)() | Devuelve un objeto [XmlReader](../../system.xml/xmlreader/) que contiene el nodo actual y sus nodos hijos. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Compara objetos por referencia. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Compara objetos por referencia. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Compara por referencia un objeto de tipo valor con nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Especialización de [Object::ReferenceEquals](../../system/object/referenceequals/) para el caso de cadena y nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Especialización de [Object::ReferenceEquals](../../system/object/referenceequals/) para el caso de cadenas. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Disminuye el contador de referencias compartidas en el valor especificado. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../../system.xml/xmlwriter/)\> [ReplaceRange](./replacerange/)([SharedPtr](../../system/sharedptr/)\<[XPathNavigator](./)\>) | Reemplaza un rango de nodos hermanos desde el nodo actual hasta el nodo especificado. |
| virtual void [ReplaceSelf](./replaceself/)([String](../../system/string/)) | Reemplaza el nodo actual con el contenido de la cadena especificada. |
| virtual void [ReplaceSelf](./replaceself/)([SharedPtr](../../system/sharedptr/)\<[XmlReader](../../system.xml/xmlreader/)\>) | Reemplaza el nodo actual con el contenido del objeto [XmlReader](../../system.xml/xmlreader/) especificado. |
| virtual void [ReplaceSelf](./replaceself/)([SharedPtr](../../system/sharedptr/)\<[XPathNavigator](./)\>) | Reemplaza el nodo actual con el contenido del objeto [XPathNavigator](./) especificado. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XPathNodeIterator](../xpathnodeiterator/)\> [Select](./select/)([String](../../system/string/)) | Selecciona un conjunto de nodos, usando la expresión [XPath](../) especificada. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XPathNodeIterator](../xpathnodeiterator/)\> [Select](./select/)([String](../../system/string/), [SharedPtr](../../system/sharedptr/)\<[IXmlNamespaceResolver](../../system.xml/ixmlnamespaceresolver/)\>) | Selecciona un conjunto de nodos usando la expresión [XPath](../) especificada con el objeto [IXmlNamespaceResolver](../../system.xml/ixmlnamespaceresolver/) especificado para resolver los prefijos de espacio de nombres. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XPathNodeIterator](../xpathnodeiterator/)\> [Select](./select/)([SharedPtr](../../system/sharedptr/)\<[XPathExpression](../xpathexpression/)\>) | Selecciona un conjunto de nodos usando el [XPathExpression](../xpathexpression/) especificado. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XPathNodeIterator](../xpathnodeiterator/)\> [SelectAncestors](./selectancestors/)([XPathNodeType](../xpathnodetype/), **bool**) | Selecciona todos los nodos ancestros del nodo actual que tienen un XPathNodeType coincidente. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XPathNodeIterator](../xpathnodeiterator/)\> [SelectAncestors](./selectancestors/)([String](../../system/string/), [String](../../system/string/), **bool**) | Selecciona todos los nodos ancestros del nodo actual que tienen el nombre local y el URI de espacio de nombres especificados. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XPathNodeIterator](../xpathnodeiterator/)\> [SelectChildren](./selectchildren/)([XPathNodeType](../xpathnodetype/)) | Selecciona todos los nodos hijos del nodo actual que tienen un XPathNodeType coincidente. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XPathNodeIterator](../xpathnodeiterator/)\> [SelectChildren](./selectchildren/)([String](../../system/string/), [String](../../system/string/)) | Selecciona todos los nodos hijos del nodo actual que tienen el nombre local y el URI de espacio de nombres especificados. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XPathNodeIterator](../xpathnodeiterator/)\> [SelectDescendants](./selectdescendants/)([XPathNodeType](../xpathnodetype/), **bool**) | Selecciona todos los nodos descendientes del nodo actual que tienen un XPathNodeType coincidente. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XPathNodeIterator](../xpathnodeiterator/)\> [SelectDescendants](./selectdescendants/)([String](../../system/string/), [String](../../system/string/), **bool**) | Selecciona todos los nodos descendientes del nodo actual con el nombre local y el URI de espacio de nombres especificados. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XPathNavigator](./)\> [SelectSingleNode](./selectsinglenode/)([String](../../system/string/)) | Selecciona un único nodo en el [XPathNavigator](./) usando la consulta [XPath](../) especificada. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XPathNavigator](./)\> [SelectSingleNode](./selectsinglenode/)([String](../../system/string/), [SharedPtr](../../system/sharedptr/)\<[IXmlNamespaceResolver](../../system.xml/ixmlnamespaceresolver/)\>) | Selecciona un único nodo en el objeto [XPathNavigator](./) usando la consulta [XPath](../) especificada con el objeto [IXmlNamespaceResolver](../../system.xml/ixmlnamespaceresolver/) especificado para resolver los prefijos de espacio de nombres. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XPathNavigator](./)\> [SelectSingleNode](./selectsinglenode/)([SharedPtr](../../system/sharedptr/)\<[XPathExpression](../xpathexpression/)\>) | Selecciona un único nodo en el [XPathNavigator](./) usando el objeto [XPathExpression](../xpathexpression/) especificado. |
| virtual void [set_InnerXml](./set_innerxml/)([String](../../system/string/)) | Establece el marcado que representa los nodos hijos del nodo actual. |
| virtual void [set_OuterXml](./set_outerxml/)([String](../../system/string/)) | Establece el marcado que representa las etiquetas de apertura y cierre del nodo actual y sus nodos hijos. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Establece el n-ésimo argumento de plantilla como un puntero débil (en lugar de compartido). Permite cambiar los punteros en contenedores a modo débil. |
| virtual void [SetTypedValue](./settypedvalue/)([SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) | Establece el valor tipado del nodo actual. |
| virtual void [SetValue](./setvalue/)([String](../../system/string/)) | Establece el valor del nodo actual. |
| int [SharedCount](../../system/object/sharedcount/)() const | Obtiene el valor actual del contador de referencias compartidas. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Incrementa el contador de referencias compartidas. No debería llamarse directamente; en su lugar, use punteros inteligentes o ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Decrementa y devuelve el contador de referencias compartidas. No debería llamarse directamente; en su lugar, use punteros inteligentes o ThisProtector. |
| [String](../../system/string/) [ToString](./tostring/)() const override | Devuelve el valor de texto del nodo actual. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementa la construcción C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementa el desbloqueo de la sentencia C# lock(). Llámese directamente o use el objeto centinela [LockContext](../../system/lockcontext/). |
| [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ValueAs](./valueas/)(const [TypeInfo](../../system/typeinfo/)\&, [SharedPtr](../../system/sharedptr/)\<[IXmlNamespaceResolver](../../system.xml/ixmlnamespaceresolver/)\>) override | Devuelve el valor del nodo actual como el Tipo especificado, usando el objeto [IXmlNamespaceResolver](../../system.xml/ixmlnamespaceresolver/) especificado para resolver los prefijos de espacio de nombres. |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ValueAs](../xpathitem/valueas/)(const [TypeInfo](../../system/typeinfo/)\&) | Devuelve el valor del elemento como el tipo especificado. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Incrementa el contador de referencias débiles. No debería llamarse directamente; en su lugar, use punteros inteligentes o ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Decrementa el contador de referencias débiles. No debería llamarse directamente; en su lugar, use punteros inteligentes o ThisProtector. |
| virtual void [WriteSubtree](./writesubtree/)([SharedPtr](../../system/sharedptr/)\<[XmlWriter](../../system.xml/xmlwriter/)\>) | Envía el nodo actual y sus nodos hijos al objeto [XmlWriter](../../system.xml/xmlwriter/) especificado. |
| virtual  [~Object](../../system/object/~object/)() | Destruye el objeto. Libera todas las estructuras de datos internas. |

## Definiciones de tipo

| Tipo definido | Descripción |
| --- | --- |
| [Ptr](./ptr/) | Un alias para puntero compartido a una instancia de esta clase. |

## Ver también

* Clase [XPathItem](../xpathitem/)
* Clase [IXPathNavigable](../ixpathnavigable/)
* Clase [IXmlNamespaceResolver](../../system.xml/ixmlnamespaceresolver/)
* Espacio de nombres [System::Xml::XPath](../)
* Biblioteca [Aspose.Slides](../../)