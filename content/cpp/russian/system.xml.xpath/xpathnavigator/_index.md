---
title: XPathNavigator
second_title: Справочник API Aspose.Slides для C++
description: Предоставляет модель курсора для навигации и редактирования XML-данных.
type: docs
weight: 66
url: /ru/system.xml.xpath/xpathnavigator/
---
## XPathNavigator класс

Provides a cursor model for navigating and editing XML data.

```cpp
class XPathNavigator : public System::Xml::XPath::XPathItem,
                       public System::Xml::XPath::IXPathNavigable,
                       public System::Xml::IXmlNamespaceResolver
```

## Методы

| Метод | Описание |
| --- | --- |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../../system.xml/xmlwriter/)\> [AppendChild](./appendchild/)() | Возвращает [XmlWriter](../../system.xml/xmlwriter/) объект, используемый для создания одного или нескольких новых дочерних узлов в конце списка дочерних узлов текущего узла. |
| virtual void [AppendChild](./appendchild/)([String](../../system/string/)) | Создаёт новый дочерний узел в конце списка дочерних узлов текущего узла, используя указанную строку XML-данных. |
| virtual void [AppendChild](./appendchild/)([SharedPtr](../../system/sharedptr/)\<[XmlReader](../../system.xml/xmlreader/)\>) | Создаёт новый дочерний узел в конце списка дочерних узлов текущего узла, используя содержимое XML из указанного объекта [XmlReader](../../system.xml/xmlreader/). |
| virtual void [AppendChild](./appendchild/)([SharedPtr](../../system/sharedptr/)\<[XPathNavigator](./)\>) | Создаёт новый дочерний узел в конце списка дочерних узлов текущего узла, используя узлы из указанного [XPathNavigator](./). |
| virtual void [AppendChildElement](./appendchildelement/)([String](../../system/string/), [String](../../system/string/), [String](../../system/string/), [String](../../system/string/)) | Создаёт новый дочерний элементный узел в конце списка дочерних узлов текущего узла, используя указанные префикс пространства имён, локальное имя и URI пространства имён со значением. |
| virtual **bool** [CheckValidity](./checkvalidity/)([SharedPtr](../../system/sharedptr/)\<[System::Xml::Schema::XmlSchemaSet](../../system.xml.schema/xmlschemaset/)\>, [System::Xml::Schema::ValidationEventHandler](../../system.xml.schema/validationeventhandler/)) | Проверяет, что XML-данные в [XPathNavigator](./) соответствуют предоставленной схеме XML [Schema](../../system.xml.schema/) definition language (XSD). |
| virtual [SharedPtr](../../system/sharedptr/)\<[XPathNavigator](./)\> [Clone](./clone/)() | При переопределении в производном классе создаёт новый [XPathNavigator](./), расположенный в том же узле, что и этот [XPathNavigator](./). |
| virtual [XmlNodeOrder](../../system.xml/xmlnodeorder/) [ComparePosition](./compareposition/)([SharedPtr](../../system/sharedptr/)\<[XPathNavigator](./)\>) | Сравнивает позицию текущего [XPathNavigator](./) с позицией указанного [XPathNavigator](./). |
| virtual [SharedPtr](../../system/sharedptr/)\<[XPathExpression](../xpathexpression/)\> [Compile](./compile/)([String](../../system/string/)) | Компилирует строку, представляющую [XPath](../) выражение, и возвращает [XPathExpression](../xpathexpression/) объект. |
| virtual void [CreateAttribute](./createattribute/)([String](../../system/string/), [String](../../system/string/), [String](../../system/string/), [String](../../system/string/)) | Создаёт атрибутный узел на текущем элементном узле, используя указанные префикс пространства имён, локальное имя и URI пространства имён со значением. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../../system.xml/xmlwriter/)\> [CreateAttributes](./createattributes/)() | Возвращает [XmlWriter](../../system.xml/xmlwriter/) объект, используемый для создания новых атрибутов на текущем элементе. |
| [SharedPtr](../../system/sharedptr/)\<[XPathNavigator](./)\> [CreateNavigator](./createnavigator/)() override | Возвращает копию [XPathNavigator](./). |
| virtual void [DeleteRange](./deleterange/)([SharedPtr](../../system/sharedptr/)\<[XPathNavigator](./)\>) | Удаляет диапазон соседних узлов от текущего узла до указанного узла. |
| virtual void [DeleteSelf](./deleteself/)() | Удаляет текущий узел и его дочерние узлы. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Сравнивает объекты, используя семантику C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Сравнивает объекты ссылочного типа в стиле C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Сравнивает объекты типa значения в стиле C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Эмулирует сравнение чисел с плавающей точкой в стиле C#, где два NaN считаются равными, хотя согласно IEC 60559:1989 NaN не равен ни одному значению, включая NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Эмулирует сравнение чисел с плавающей точкой в стиле C#, где два NaN считаются равными, хотя согласно IEC 60559:1989 NaN не равен ни одному значению, включая NaN. |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [Evaluate](./evaluate/)([String](../../system/string/)) | Вычисляет указанное [XPath](../) выражение и возвращает типизированный результат. |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [Evaluate](./evaluate/)([String](../../system/string/), [SharedPtr](../../system/sharedptr/)\<[IXmlNamespaceResolver](../../system.xml/ixmlnamespaceresolver/)\>) | Вычисляет указанное [XPath](../) выражение и возвращает типизированный результат, используя указанный объект [IXmlNamespaceResolver](../../system.xml/ixmlnamespaceresolver/) для разрешения префиксов пространств имён в [XPath](../) выражении. |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [Evaluate](./evaluate/)([SharedPtr](../../system/sharedptr/)\<[XPathExpression](../xpathexpression/)\>) | Вычисляет [XPathExpression](../xpathexpression/) и возвращает типизированный результат. |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [Evaluate](./evaluate/)([SharedPtr](../../system/sharedptr/)\<[XPathExpression](../xpathexpression/)\>, [SharedPtr](../../system/sharedptr/)\<[XPathNodeIterator](../xpathnodeiterator/)\>) | Использует предоставленный контекст для вычисления [XPathExpression](../xpathexpression/) и возвращает типизированный результат. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Только для внутреннего использования. |
| virtual [String](../../system/string/) [get_BaseURI](./get_baseuri/)() | При переопределении в производном классе получает базовый URI текущего узла. |
| virtual **bool** [get_CanEdit](./get_canedit/)() | Возвращает значение, указывающее, может ли [XPathNavigator](./) редактировать базовые XML-данные. |
| virtual **bool** [get_HasAttributes](./get_hasattributes/)() | Возвращает значение, указывающее, имеет ли текущий узел какие-либо атрибуты. |
| virtual **bool** [get_HasChildren](./get_haschildren/)() | Возвращает значение, указывающее, имеет ли текущий узел какие-либо дочерние узлы. |
| virtual [String](../../system/string/) [get_InnerXml](./get_innerxml/)() | Возвращает разметку, представляющую дочерние узлы текущего узла. |
| virtual **bool** [get_IsEmptyElement](./get_isemptyelement/)() | При переопределении в производном классе получает значение, указывающее, является ли текущий узел пустым элементом без закрывающего тега. |
| **bool** [get_IsNode](./get_isnode/)() override | Возвращает значение, указывающее, представляет ли текущий узел [XPath](../) узел. |
| virtual [String](../../system/string/) [get_LocalName](./get_localname/)() | При переопределении в производном классе получает [XPathNavigator::get_Name](./get_name/) текущего узла без любого префикса пространства имён. |
| virtual [String](../../system/string/) [get_Name](./get_name/)() | При переопределении в производном классе получает квалифицированное имя текущего узла. |
| virtual [String](../../system/string/) [get_NamespaceURI](./get_namespaceuri/)() | При переопределении в производном классе получает URI пространства имён текущего узла. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlNameTable](../../system.xml/xmlnametable/)\> [get_NameTable](./get_nametable/)() | При переопределении в производном классе получает [XmlNameTable](../../system.xml/xmlnametable/) [XPathNavigator](./). |
| static [SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IEqualityComparer](../../system.collections.generic/iequalitycomparer/)\<[SharedPtr](../../system/sharedptr/)\<[XPathNavigator](./)\>\>\> [get_NavigatorComparer](./get_navigatorcomparer/)() | Возвращает [Collections::IEqualityComparer](../../system.collections/iequalitycomparer/) объект, используемый для сравнения на равенство объектов [XPathNavigator](./). |
| virtual [XPathNodeType](../xpathnodetype/) [get_NodeType](./get_nodetype/)() | При переопределении в производном классе получает XPathNodeType текущего узла. |
| virtual [String](../../system/string/) [get_OuterXml](./get_outerxml/)() | Возвращает разметку, представляющую открывающие и закрывающие теги текущего узла и его дочерних узлов. |
| virtual [String](../../system/string/) [get_Prefix](./get_prefix/)() | При переопределении в производном классе получает префикс пространства имён, связанный с текущим узлом. |
| virtual [SharedPtr](../../system/sharedptr/)\<[System::Xml::Schema::IXmlSchemaInfo](../../system.xml.schema/ixmlschemainfo/)\> [get_SchemaInfo](./get_schemainfo/)() | Возвращает информацию схемы, назначенную текущему узлу в результате проверки схемы. |
| [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [get_TypedValue](./get_typedvalue/)() override | Возвращает текущий узел как упакованный объект наиболее подходящего типа. |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [get_UnderlyingObject](./get_underlyingobject/)() | Используется реализациями [XPathNavigator](./), которые предоставляют «виртуализированный» XML-вид над хранилищем, для доступа к базовым объектам. |
| virtual [String](../../system/string/) [get_Value](../xpathitem/get_value/)() | При переопределении в производном классе получает **string** значение элемента. |
| **bool** [get_ValueAsBoolean](./get_valueasboolean/)() override | Возвращает значение текущего узла как [Boolean](../../system/boolean/). |
| [DateTime](../../system/datetime/) [get_ValueAsDateTime](./get_valueasdatetime/)() override | Возвращает значение текущего узла как [DateTime](../../system/datetime/). |
| **double** [get_ValueAsDouble](./get_valueasdouble/)() override | Возвращает значение текущего узла как [Double](../../system/double/). |
| **int32_t** [get_ValueAsInt](./get_valueasint/)() override | Возвращает значение текущего узла как [Int32](../../system/int32/). |
| **int64_t** [get_ValueAsLong](./get_valueaslong/)() override | Возвращает значение текущего узла как [Int64](../../system/int64/). |
| [TypeInfo](../../system/typeinfo/) [get_ValueType](./get_valuetype/)() override | Возвращает тип текущего узла. |
| virtual [String](../../system/string/) [get_XmlLang](./get_xmllang/)() | Возвращает **xml:lang** область для текущего узла. |
| [SharedPtr](../../system/sharedptr/)\<[System::Xml::Schema::XmlSchemaType](../../system.xml.schema/xmlschematype/)\> [get_XmlType](./get_xmltype/)() override | Возвращает информацию XmlSchemaType для текущего узла. |
| virtual [String](../../system/string/) [GetAttribute](./getattribute/)([String](../../system/string/), [String](../../system/string/)) | Возвращает значение атрибута с указанным локальным именем и URI пространства имён. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Получает структуру счётчика ссылок, связанную с объектом. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Аналог метода C# [Object.GetHashCode()](../../system/object/gethashcode/). Позволяет вычислять хеш пользовательских объектов. |
| virtual [String](../../system/string/) [GetNamespace](./getnamespace/)([String](../../system/string/)) | Возвращает значение узла пространства имён, соответствующего указанному локальному имени. |
| [SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IDictionary](../../system.collections.generic/idictionary/)\<[String](../../system/string/), [String](../../system/string/)\>\> [GetNamespacesInScope](./getnamespacesinscope/)([XmlNamespaceScope](../../system.xml/xmlnamespacescope/)) override | Возвращает доступные в области действия пространства имён текущего узла. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Получает фактический тип объекта. Аналог вызова C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../../system.xml/xmlwriter/)\> [InsertAfter](./insertafter/)() | Возвращает [XmlWriter](../../system.xml/xmlwriter/) объект, используемый для создания нового соседнего узла после текущего выбранного узла. |
| virtual void [InsertAfter](./insertafter/)([String](../../system/string/)) | Создаёт новый соседний узел после текущего выбранного узла, используя указанную строку XML. |
| virtual void [InsertAfter](./insertafter/)([SharedPtr](../../system/sharedptr/)\<[XmlReader](../../system.xml/xmlreader/)\>) | Создаёт новый соседний узел после текущего выбранного узла, используя содержимое XML из указанного объекта [XmlReader](../../system.xml/xmlreader/). |
| virtual void [InsertAfter](./insertafter/)([SharedPtr](../../system/sharedptr/)\<[XPathNavigator](./)\>) | Создаёт новый соседний узел после текущего выбранного узла, используя узлы из указанного объекта [XPathNavigator](./). |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../../system.xml/xmlwriter/)\> [InsertBefore](./insertbefore/)() | Возвращает [XmlWriter](../../system.xml/xmlwriter/) объект, используемый для создания нового соседнего узла перед текущим выбранным узлом. |
| virtual void [InsertBefore](./insertbefore/)([String](../../system/string/)) | Создаёт новый соседний узел перед текущим выбранным узлом, используя указанную строку XML. |
| virtual void [InsertBefore](./insertbefore/)([SharedPtr](../../system/sharedptr/)\<[XmlReader](../../system.xml/xmlreader/)\>) | Создаёт новый соседний узел перед текущим выбранным узлом, используя содержимое XML из указанного объекта [XmlReader](../../system.xml/xmlreader/). |
| virtual void [InsertBefore](./insertbefore/)([SharedPtr](../../system/sharedptr/)\<[XPathNavigator](./)\>) | Создаёт новый соседний узел перед текущим выбранным узлом, используя узлы из указанного [XPathNavigator](./). |
| virtual void [InsertElementAfter](./insertelementafter/)([String](../../system/string/), [String](../../system/string/), [String](../../system/string/), [String](../../system/string/)) | Создаёт новый соседний элементный узел после текущего узла, используя указанные префикс пространства имён, локальное имя и URI пространства имён со значением. |
| virtual void [InsertElementBefore](./insertelementbefore/)([String](../../system/string/), [String](../../system/string/), [String](../../system/string/), [String](../../system/string/)) | Создаёт новый соседний элементный узел перед текущим узлом, используя указанные префикс пространства имён, локальное имя и URI пространства имён со значением. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Проверяет, представляет ли объект экземпляр типа, описанного targetType. Аналог оператора C# 'is'. |
| virtual **bool** [IsDescendant](./isdescendant/)([SharedPtr](../../system/sharedptr/)\<[XPathNavigator](./)\>) | Определяет, является ли указанный [XPathNavigator](./) потомком текущего [XPathNavigator](./). |
| virtual **bool** [IsSamePosition](./issameposition/)([SharedPtr](../../system/sharedptr/)\<[XPathNavigator](./)\>) | При переопределении в производном классе определяет, находится ли текущий [XPathNavigator](./) в той же позиции, что и указанный [XPathNavigator](./). |
| void [Lock](../../system/object/lock/)() | Реализует блокировку оператора C# lock(). Вызывайте напрямую или используйте объект-сторож [LockContext](../../system/lockcontext/). |
| [String](../../system/string/) [LookupNamespace](./lookupnamespace/)(const [String](../../system/string/)\&) override | Возвращает URI пространства имён для указанного префикса. |
| [String](../../system/string/) [LookupPrefix](./lookupprefix/)(const [String](../../system/string/)\&) override | Возвращает префикс, объявленный для указанного URI пространства имён. |
| virtual **bool** [Matches](./matches/)([SharedPtr](../../system/sharedptr/)\<[XPathExpression](../xpathexpression/)\>) | Определяет, соответствует ли текущий узел указанному [XPathExpression](../xpathexpression/). |
| virtual **bool** [Matches](./matches/)([String](../../system/string/)) | Определяет, соответствует ли текущий узел указанному [XPath](../) выражению. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Аналог метода C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Позволяет клонировать пользовательские типы. |
| virtual **bool** [MoveTo](./moveto/)([SharedPtr](../../system/sharedptr/)\<[XPathNavigator](./)\>) | При переопределении в производном классе перемещает [XPathNavigator](./) в ту же позицию, что и указанный [XPathNavigator](./). |
| virtual **bool** [MoveToAttribute](./movetoattribute/)([String](../../system/string/), [String](../../system/string/)) | Перемещает [XPathNavigator](./) к атрибуту с совпадающим локальным именем и URI пространства имён. |
| virtual **bool** [MoveToChild](./movetochild/)([String](../../system/string/), [String](../../system/string/)) | Перемещает [XPathNavigator](./) к дочернему узлу с указанным локальным именем и URI пространства имён. |
| virtual **bool** [MoveToChild](./movetochild/)([XPathNodeType](../xpathnodetype/)) | Перемещает [XPathNavigator](./) к дочернему узлу указанного XPathNodeType. |
| virtual **bool** [MoveToFirst](./movetofirst/)() | Перемещает [XPathNavigator](./) к первому соседнему узлу текущего узла. |
| virtual **bool** [MoveToFirstAttribute](./movetofirstattribute/)() | При переопределении в производном классе перемещает [XPathNavigator](./) к первому атрибуту текущего узла. |
| virtual **bool** [MoveToFirstChild](./movetofirstchild/)() | При переопределении в производном классе перемещает [XPathNavigator](./) к первому дочернему узлу текущего узла. |
| virtual **bool** [MoveToFirstNamespace](./movetofirstnamespace/)([XPathNamespaceScope](../xpathnamespacescope/)) | При переопределении в производном классе перемещает [XPathNavigator](./) к первому узлу пространства имён, соответствующему указанному XPathNamespaceScope. |
| **bool** [MoveToFirstNamespace](./movetofirstnamespace/)() | Перемещает [XPathNavigator](./) к первому узлу пространства имён текущего узла. |
| virtual **bool** [MoveToFollowing](./movetofollowing/)([String](../../system/string/), [String](../../system/string/)) | Перемещает [XPathNavigator](./) к элементу с указанным локальным именем и URI пространства имён в порядке следования в документе. |
| virtual **bool** [MoveToFollowing](./movetofollowing/)([String](../../system/string/), [String](../../system/string/), [SharedPtr](../../system/sharedptr/)\<[XPathNavigator](./)\>) | Перемещает [XPathNavigator](./) к элементу с указанным локальным именем и URI пространства имён, до указанной границы, в порядке следования в документе. |
| virtual **bool** [MoveToFollowing](./movetofollowing/)([XPathNodeType](../xpathnodetype/)) | Перемещает [XPathNavigator](./) к следующему элементу указанного XPathNodeType в порядке следования в документе. |
| virtual **bool** [MoveToFollowing](./movetofollowing/)([XPathNodeType](../xpathnodetype/), [SharedPtr](../../system/sharedptr/)\<[XPathNavigator](./)\>) | Перемещает [XPathNavigator](./) к следующему элементу указанного XPathNodeType, до указанной границы, в порядке следования в документе. |
| virtual **bool** [MoveToId](./movetoid/)([String](../../system/string/)) | При переопределении в производном классе переходит к узлу, имеющему атрибут типа **ID**, значение которого совпадает с указанным [String](../../system/string/). |
| virtual **bool** [MoveToNamespace](./movetonamespace/)([String](../../system/string/)) | Перемещает [XPathNavigator](./) к узлу пространства имён с указанным префиксом. |
| virtual **bool** [MoveToNext](./movetonext/)() | При переопределении в производном классе перемещает [XPathNavigator](./) к следующему соседнему узлу текущего узла. |
| virtual **bool** [MoveToNext](./movetonext/)([String](../../system/string/), [String](../../system/string/)) | Перемещает [XPathNavigator](./) к следующему соседнему узлу с указанным локальным именем и URI пространства имён. |
| virtual **bool** [MoveToNext](./movetonext/)([XPathNodeType](../xpathnodetype/)) | Перемещает [XPathNavigator](./) к следующему соседнему узлу текущего узла, соответствующему указанному XPathNodeType. |
| virtual **bool** [MoveToNextAttribute](./movetonextattribute/)() | При переопределении в производном классе перемещает [XPathNavigator](./) к следующему атрибуту. |
| virtual **bool** [MoveToNextNamespace](./movetonextnamespace/)([XPathNamespaceScope](../xpathnamespacescope/)) | При переопределении в производном классе перемещает [XPathNavigator](./) к следующему узлу пространства имён, соответствующему указанному XPathNamespaceScope. |
| **bool** [MoveToNextNamespace](./movetonextnamespace/)() | Перемещает [XPathNavigator](./) к следующему узлу пространства имён. |
| virtual **bool** [MoveToParent](./movetoparent/)() | При переопределении в производном классе перемещает [XPathNavigator](./) к родительскому узлу текущего узла. |
| virtual **bool** [MoveToPrevious](./movetoprevious/)() | При переопределении в производном классе перемещает [XPathNavigator](./) к предыдущему соседнему узлу текущего узла. |
| virtual void [MoveToRoot](./movetoroot/)() | Перемещает [XPathNavigator](./) к корневому узлу, к которому принадлежит текущий узел. |
|  [Object](../../system/object/object/)() | Создаёт объект. Инициализирует все внутренние структуры данных. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Конструктор копирования. На самом деле ничего не копирует, только инициализирует новый объект и позволяет копировать подклассы. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Оператор присваивания. На самом деле ничего не копирует, только инициализирует новый объект и позволяет копировать подклассы. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../../system.xml/xmlwriter/)\> [PrependChild](./prependchild/)() | Возвращает [XmlWriter](../../system.xml/xmlwriter/) объект, используемый для создания нового дочернего узла в начале списка дочерних узлов текущего узла. |
| virtual void [PrependChild](./prependchild/)([String](../../system/string/)) | Создаёт новый дочерний узел в начале списка дочерних узлов текущего узла, используя указанную строку XML. |
| virtual void [PrependChild](./prependchild/)([SharedPtr](../../system/sharedptr/)\<[XmlReader](../../system.xml/xmlreader/)\>) | Создаёт новый дочерний узел в начале списка дочерних узлов текущего узла, используя содержимое XML из указанного объекта [XmlReader](../../system.xml/xmlreader/). |
| virtual void [PrependChild](./prependchild/)([SharedPtr](../../system/sharedptr/)\<[XPathNavigator](./)\>) | Создаёт новый дочерний узел в начале списка дочерних узлов текущего узла, используя узлы из указанного объекта [XPathNavigator](./). |
| virtual void [PrependChildElement](./prependchildelement/)([String](../../system/string/), [String](../../system/string/), [String](../../system/string/), [String](../../system/string/)) | Создаёт новый дочерний элементный узел в начале списка дочерних узлов текущего узла, используя указанные префикс пространства имён, локальное имя и URI пространства имён со значением. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlReader](../../system.xml/xmlreader/)\> [ReadSubtree](./readsubtree/)() | Возвращает [XmlReader](../../system.xml/xmlreader/) объект, содержащий текущий узел и его дочерние узлы. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Сравнивает объекты по ссылке. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Сравнивает объекты по ссылке. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Сравнивает объект типa значения со значением nullptr по ссылке. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Специализация [Object::ReferenceEquals](../../system/object/referenceequals/) для случая строки и nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Специализация [Object::ReferenceEquals](../../system/object/referenceequals/) для случая строк. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Уменьшает счётчик общих ссылок на указанное значение. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../../system.xml/xmlwriter/)\> [ReplaceRange](./replacerange/)([SharedPtr](../../system/sharedptr/)\<[XPathNavigator](./)\>) | Заменяет диапазон соседних узлов от текущего узла до указанного узла. |
| virtual void [ReplaceSelf](./replaceself/)([String](../../system/string/)) | Заменяет текущий узел содержимым указанной строки. |
| virtual void [ReplaceSelf](./replaceself/)([SharedPtr](../../system/sharedptr/)\<[XmlReader](../../system.xml/xmlreader/)\>) | Заменяет текущий узел содержимым указанного объекта [XmlReader](../../system.xml/xmlreader/). |
| virtual void [ReplaceSelf](./replaceself/)([SharedPtr](../../system/sharedptr/)\<[XPathNavigator](./)\>) | Заменяет текущий узел содержимым указанного объекта [XPathNavigator](./). |
| virtual [SharedPtr](../../system/sharedptr/)\<[XPathNodeIterator](../xpathnodeiterator/)\> [Select](./select/)([String](../../system/string/)) | Выбирает набор узлов, используя указанное [XPath](../) выражение. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XPathNodeIterator](../xpathnodeiterator/)\> [Select](./select/)([String](../../system/string/), [SharedPtr](../../system/sharedptr/)\<[IXmlNamespaceResolver](../../system.xml/ixmlnamespaceresolver/)\>) | Выбирает набор узлов, используя указанное [XPath](../) выражение с объектом [IXmlNamespaceResolver](../../system.xml/ixmlnamespaceresolver/) для разрешения префиксов пространств имён. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XPathNodeIterator](../xpathnodeiterator/)\> [Select](./select/)([SharedPtr](../../system/sharedptr/)\<[XPathExpression](../xpathexpression/)\>) | Выбирает набор узлов, используя указанный [XPathExpression](../xpathexpression/). |
| virtual [SharedPtr](../../system/sharedptr/)\<[XPathNodeIterator](../xpathnodeiterator/)\> [SelectAncestors](./selectancestors/)([XPathNodeType](../xpathnodetype/), **bool**) | Выбирает все узлы-предки текущего узла, имеющие совпадающий XPathNodeType. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XPathNodeIterator](../xpathnodeiterator/)\> [SelectAncestors](./selectancestors/)([String](../../system/string/), [String](../../system/string/), **bool**) | Выбирает все узлы-предки текущего узла, имеющие указанные локальное имя и URI пространства имён. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XPathNodeIterator](../xpathnodeiterator/)\> [SelectChildren](./selectchildren/)([XPathNodeType](../xpathnodetype/)) | Выбирает все дочерние узлы текущего узла, имеющие совпадающий XPathNodeType. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XPathNodeIterator](../xpathnodeiterator/)\> [SelectChildren](./selectchildren/)([String](../../system/string/), [String](../../system/string/)) | Выбирает все дочерние узлы текущего узла, имеющие указанное локальное имя и URI пространства имён. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XPathNodeIterator](../xpathnodeiterator/)\> [SelectDescendants](./selectdescendants/)([XPathNodeType](../xpathnodetype/), **bool**) | Выбирает все потомки текущего узла, имеющие совпадающий XPathNodeType. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XPathNodeIterator](../xpathnodeiterator/)\> [SelectDescendants](./selectdescendants/)([String](../../system/string/), [String](../../system/string/), **bool**) | Выбирает всех потомков текущего узла, имеющих указанное локальное имя и URI пространства имён. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XPathNavigator](./)\> [SelectSingleNode](./selectsinglenode/)([String](../../system/string/)) | Выбирает один узел в [XPathNavigator](./) с помощью указанного запроса [XPath](../). |
| virtual [SharedPtr](../../system/sharedptr/)\<[XPathNavigator](./)\> [SelectSingleNode](./selectsinglenode/)([String](../../system/string/), [SharedPtr](../../system/sharedptr/)\<[IXmlNamespaceResolver](../../system.xml/ixmlnamespaceresolver/)\>) | Выбирает один узел в объекте [XPathNavigator](./) с помощью указанного запроса [XPath](../) и объекта [IXmlNamespaceResolver](../../system.xml/ixmlnamespaceresolver/) для разрешения префиксов пространств имён. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XPathNavigator](./)\> [SelectSingleNode](./selectsinglenode/)([SharedPtr](../../system/sharedptr/)\<[XPathExpression](../xpathexpression/)\>) | Выбирает один узел в [XPathNavigator](./) с помощью указанного объекта [XPathExpression](../xpathexpression/). |
| virtual void [set_InnerXml](./set_innerxml/)([String](../../system/string/)) | Устанавливает разметку, представляющую дочерние узлы текущего узла. |
| virtual void [set_OuterXml](./set_outerxml/)([String](../../system/string/)) | Устанавливает разметку, представляющую открывающие и закрывающие теги текущего узла и его дочерних узлов. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Устанавливает n-й параметр шаблона как слабый указатель (в отличие от shared). Позволяет переключать указатели в контейнерах в слабый режим. |
| virtual void [SetTypedValue](./settypedvalue/)([SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) | Устанавливает типизированное значение текущего узла. |
| virtual void [SetValue](./setvalue/)([String](../../system/string/)) | Устанавливает значение текущего узла. |
| int [SharedCount](../../system/object/sharedcount/)() const | Получает текущее значение счётчика общих ссылок. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Увеличивает счётчик общих ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Уменьшает и возвращает счётчик общих ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
| [String](../../system/string/) [ToString](./tostring/)() const override | Возвращает текстовое значение текущего узла. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Реализует конструкцию C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Реализует разблокировку оператора C# lock(). Вызывайте напрямую или используйте объект-сторож [LockContext](../../system/lockcontext/). |
| [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ValueAs](./valueas/)(const [TypeInfo](../../system/typeinfo/)\&, [SharedPtr](../../system/sharedptr/)\<[IXmlNamespaceResolver](../../system.xml/ixmlnamespaceresolver/)\>) override | Возвращает значение текущего узла как указанный Type, используя указанный объект [IXmlNamespaceResolver](../../system.xml/ixmlnamespaceresolver/) для разрешения префиксов пространств имён. |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ValueAs](../xpathitem/valueas/)(const [TypeInfo](../../system/typeinfo/)\&) | Возвращает значение элемента как указанный тип. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Увеличивает счётчик слабых ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Уменьшает счётчик слабых ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
| virtual void [WriteSubtree](./writesubtree/)([SharedPtr](../../system/sharedptr/)\<[XmlWriter](../../system.xml/xmlwriter/)\>) | Передаёт текущий узел и его дочерние узлы в указанный объект [XmlWriter](../../system.xml/xmlwriter/). |
| virtual  [~Object](../../system/object/~object/)() | Уничтожает объект. Освобождает все внутренние структуры данных. |

## Типedefы

| Типedef | Описание |
| --- | --- |
| [Ptr](./ptr/) | Псевдоним для shared pointer к экземпляру этого класса. |

## См. также

* Класс [XPathItem](../xpathitem/)
* Класс [IXPathNavigable](../ixpathnavigable/)
* Класс [IXmlNamespaceResolver](../../system.xml/ixmlnamespaceresolver/)
* Пространство имён [System::Xml::XPath](../)
* Библиотека [Aspose.Slides](../../)