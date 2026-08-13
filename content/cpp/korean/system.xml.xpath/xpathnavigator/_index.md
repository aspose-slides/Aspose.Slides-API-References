---
title: XPathNavigator
second_title: Aspose.Slides for C++ API 레퍼런스
description: XML 데이터를 탐색하고 편집하기 위한 커서 모델을 제공합니다.
type: docs
weight: 66
url: /ko/system.xml.xpath/xpathnavigator/
---
## XPathNavigator 클래스

XML 데이터를 탐색하고 편집하기 위한 커서 모델을 제공합니다.

```cpp
class XPathNavigator : public System::Xml::XPath::XPathItem,
                       public System::Xml::XPath::IXPathNavigable,
                       public System::Xml::IXmlNamespaceResolver
```

## 메서드

| Method | Description |
| --- | --- |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../../system.xml/xmlwriter/)\> [AppendChild](./appendchild/)() | [XmlWriter](../../system.xml/xmlwriter/) 객체를 반환합니다. 이 객체는 현재 노드의 자식 노드 목록 끝에 하나 이상의 새 자식 노드를 만들 때 사용됩니다. |
| virtual void [AppendChild](./appendchild/)([String](../../system/string/)) | 지정된 XML 데이터 문자열을 사용하여 현재 노드의 자식 노드 목록 끝에 새 자식 노드를 생성합니다. |
| virtual void [AppendChild](./appendchild/)([SharedPtr](../../system/sharedptr/)\<[XmlReader](../../system.xml/xmlreader/)\>) | 지정된 [XmlReader](../../system.xml/xmlreader/) 객체의 XML 내용을 사용하여 현재 노드의 자식 노드 목록 끝에 새 자식 노드를 생성합니다. |
| virtual void [AppendChild](./appendchild/)([SharedPtr](../../system/sharedptr/)\<[XPathNavigator](./)\>) | 지정된 [XPathNavigator](./)에 있는 노드를 사용하여 현재 노드의 자식 노드 목록 끝에 새 자식 노드를 생성합니다. |
| virtual void [AppendChildElement](./appendchildelement/)([String](../../system/string/), [String](../../system/string/), [String](../../system/string/), [String](../../system/string/)) | 지정된 네임스페이스 접두사, 로컬 이름 및 네임스페이스 URI와 값을 사용하여 현재 노드의 자식 노드 목록 끝에 새 자식 요소 노드를 생성합니다. |
| virtual **bool** [CheckValidity](./checkvalidity/)([SharedPtr](../../system/sharedptr/)\<[System::Xml::Schema::XmlSchemaSet](../../system.xml.schema/xmlschemaset/)\>, [System::Xml::Schema::ValidationEventHandler](../../system.xml.schema/validationeventhandler/)) | [XPathNavigator](./)에 있는 XML 데이터가 제공된 XML [Schema](../../system.xml.schema/) 정의 언어(XSD) 스키마에 부합하는지 확인합니다. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XPathNavigator](./)\> [Clone](./clone/)() | 파생 클래스에서 재정의되면, 이 [XPathNavigator](./)와 동일한 노드에 위치한 새 [XPathNavigator](./)를 생성합니다. |
| virtual [XmlNodeOrder](../../system.xml/xmlnodeorder/) [ComparePosition](./compareposition/)([SharedPtr](../../system/sharedptr/)\<[XPathNavigator](./)\>) | 현재 [XPathNavigator](./)의 위치를 지정된 [XPathNavigator](./)의 위치와 비교합니다. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XPathExpression](../xpathexpression/)\> [Compile](./compile/)([String](../../system/string/)) | [XPath](../) 식을 나타내는 문자열을 컴파일하고 [XPathExpression](../xpathexpression/) 객체를 반환합니다. |
| virtual void [CreateAttribute](./createattribute/)([String](../../system/string/), [String](../../system/string/), [String](../../system/string/), [String](../../system/string/)) | 지정된 네임스페이스 접두사, 로컬 이름 및 네임스페이스 URI와 값을 사용하여 현재 요소 노드에 속성 노드를 생성합니다. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../../system.xml/xmlwriter/)\> [CreateAttributes](./createattributes/)() | [XmlWriter](../../system.xml/xmlwriter/) 객체를 반환합니다. 이 객체는 현재 요소에 새 속성을 만들 때 사용됩니다. |
| [SharedPtr](../../system/sharedptr/)\<[XPathNavigator](./)\> [CreateNavigator](./createnavigator/)() override | [XPathNavigator](./)의 복사본을 반환합니다. |
| virtual void [DeleteRange](./deleterange/)([SharedPtr](../../system/sharedptr/)\<[XPathNavigator](./)\>) | 현재 노드부터 지정된 노드까지 형제 노드 범위를 삭제합니다. |
| virtual void [DeleteSelf](./deleteself/)() | 현재 노드와 그 자식 노드를 삭제합니다. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) 의미론을 사용하여 객체를 비교합니다. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# 스타일로 참조 형식 객체를 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# 스타일로 값 형식 객체를 비교합니다. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | IEC 60559:1989에 따르면 NaN은 어떤 값과도 같지 않지만, 두 NaN을 동일하게 간주하는 C# 스타일 부동소수점 비교를 에뮬레이션합니다. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | IEC 60559:1989에 따르면 NaN은 어떤 값과도 같지 않지만, 두 NaN을 동일하게 간주하는 C# 스타일 부동소수점 비교를 에뮬레이션합니다. |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [Evaluate](./evaluate/)([String](../../system/string/)) | 지정된 [XPath](../) 식을 평가하고 유형화된 결과를 반환합니다. |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [Evaluate](./evaluate/)([String](../../system/string/), [SharedPtr](../../system/sharedptr/)\<[IXmlNamespaceResolver](../../system.xml/ixmlnamespaceresolver/)\>) | 지정된 [XPath](../) 식을 평가하고 유형화된 결과를 반환합니다. [IXmlNamespaceResolver](../../system.xml/ixmlnamespaceresolver/) 객체를 사용하여 [XPath](../) 식의 네임스페이스 접두사를 해석합니다. |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [Evaluate](./evaluate/)([SharedPtr](../../system/sharedptr/)\<[XPathExpression](../xpathexpression/)\>) | [XPathExpression](../xpathexpression/)을 평가하고 유형화된 결과를 반환합니다. |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [Evaluate](./evaluate/)([SharedPtr](../../system/sharedptr/)\<[XPathExpression](../xpathexpression/)\>, [SharedPtr](../../system/sharedptr/)\<[XPathNodeIterator](../xpathnodeiterator/)\>) | 제공된 컨텍스트를 사용하여 [XPathExpression](../xpathexpression/)를 평가하고 유형화된 결과를 반환합니다. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 내부 용도로만 사용됩니다. |
| virtual [String](../../system/string/) [get_BaseURI](./get_baseuri/)() | 파생 클래스에서 재정의되면, 현재 노드의 기본 URI를 가져옵니다. |
| virtual **bool** [get_CanEdit](./get_canedit/)() | [XPathNavigator](./)가 기본 XML 데이터를 편집할 수 있는지 여부를 나타내는 값을 반환합니다. |
| virtual **bool** [get_HasAttributes](./get_hasattributes/)() | 현재 노드에 속성이 있는지 여부를 나타내는 값을 반환합니다. |
| virtual **bool** [get_HasChildren](./get_haschildren/)() | 현재 노드에 자식 노드가 있는지 여부를 나타내는 값을 반환합니다. |
| virtual [String](../../system/string/) [get_InnerXml](./get_innerxml/)() | 현재 노드의 자식 노드를 나타내는 마크업을 반환합니다. |
| virtual **bool** [get_IsEmptyElement](./get_isemptyelement/)() | 파생 클래스에서 재정의되면, 현재 노드가 종료 태그 없이 빈 요소인지 여부를 나타내는 값을 가져옵니다. |
| **bool** [get_IsNode](./get_isnode/)() override | 현재 노드가 [XPath](../) 노드를 나타내는지 여부를 나타내는 값을 반환합니다. |
| virtual [String](../../system/string/) [get_LocalName](./get_localname/)() | 파생 클래스에서 재정의되면, 네임스페이스 접두사 없이 현재 노드의 [XPathNavigator::get_Name](./get_name/)를 가져옵니다. |
| virtual [String](../../system/string/) [get_Name](./get_name/)() | 파생 클래스에서 재정의되면, 현재 노드의 정규화된 이름을 가져옵니다. |
| virtual [String](../../system/string/) [get_NamespaceURI](./get_namespaceuri/)() | 파생 클래스에서 재정의되면, 현재 노드의 네임스페이스 URI를 가져옵니다. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlNameTable](../../system.xml/xmlnametable/)\> [get_NameTable](./get_nametable/)() | 파생 클래스에서 재정의되면, [XPathNavigator](./)의 [XmlNameTable](../../system.xml/xmlnametable/)를 가져옵니다. |
| static [SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IEqualityComparer](../../system.collections.generic/iequalitycomparer/)\<[SharedPtr](../../system/sharedptr/)\<[XPathNavigator](./)\>\>\> [get_NavigatorComparer](./get_navigatorcomparer/)() | [XPathNavigator](./) 객체의 동등성 비교에 사용되는 [Collections::IEqualityComparer](../../system.collections/iequalitycomparer/)를 반환합니다. |
| virtual [XPathNodeType](../xpathnodetype/) [get_NodeType](./get_nodetype/)() | 파생 클래스에서 재정의되면, 현재 노드의 XPathNodeType을 가져옵니다. |
| virtual [String](../../system/string/) [get_OuterXml](./get_outerxml/)() | 현재 노드와 그 자식 노드의 시작 및 종료 태그를 나타내는 마크업을 반환합니다. |
| virtual [String](../../system/string/) [get_Prefix](./get_prefix/)() | 파생 클래스에서 재정의되면, 현재 노드와 연관된 네임스페이스 접두사를 가져옵니다. |
| virtual [SharedPtr](../../system/sharedptr/)\<[System::Xml::Schema::IXmlSchemaInfo](../../system.xml.schema/ixmlschemainfo/)\> [get_SchemaInfo](./get_schemainfo/)() | 스키마 검증 결과로 현재 노드에 할당된 스키마 정보를 반환합니다. |
| [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [get_TypedValue](./get_typedvalue/)() override | 현재 노드를 가장 적절한 유형의 박싱된 객체로 반환합니다. |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [get_UnderlyingObject](./get_underlyingobject/)() | [XPathNavigator](./) 구현에서 저장소에 대한 "가상화된" XML 뷰를 제공하며, 기본 객체에 대한 접근을 제공합니다. |
| virtual [String](../../system/string/) [get_Value](../xpathitem/get_value/)() | 파생 클래스에서 재정의되면, 항목의 **string** 값을 가져옵니다. |
| **bool** [get_ValueAsBoolean](./get_valueasboolean/)() override | 현재 노드의 값을 [Boolean](../../system/boolean/)로 반환합니다. |
| [DateTime](../../system/datetime/) [get_ValueAsDateTime](./get_valueasdatetime/)() override | 현재 노드의 값을 [DateTime](../../system/datetime/)로 반환합니다. |
| **double** [get_ValueAsDouble](./get_valueasdouble/)() override | 현재 노드의 값을 [Double](../../system/double/)로 반환합니다. |
| **int32_t** [get_ValueAsInt](./get_valueasint/)() override | 현재 노드의 값을 [Int32](../../system/int32/)로 반환합니다. |
| **int64_t** [get_ValueAsLong](./get_valueaslong/)() override | 현재 노드의 값을 [Int64](../../system/int64/)로 반환합니다. |
| [TypeInfo](../../system/typeinfo/) [get_ValueType](./get_valuetype/)() override | 현재 노드의 유형을 반환합니다. |
| virtual [String](../../system/string/) [get_XmlLang](./get_xmllang/)() | 현재 노드의 **xml:lang** 범위를 반환합니다. |
| [SharedPtr](../../system/sharedptr/)\<[System::Xml::Schema::XmlSchemaType](../../system.xml.schema/xmlschematype/)\> [get_XmlType](./get_xmltype/)() override | 현재 노드에 대한 XmlSchemaType 정보를 반환합니다. |
| virtual [String](../../system/string/) [GetAttribute](./getattribute/)([String](../../system/string/), [String](../../system/string/)) | 지정된 로컬 이름과 네임스페이스 URI를 가진 속성의 값을 반환합니다. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | 객체와 연결된 참조 카운터 데이터 구조를 가져옵니다. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) 메서드와 유사합니다. 사용자 정의 객체의 해시화를 가능하게 합니다. |
| virtual [String](../../system/string/) [GetNamespace](./getnamespace/)([String](../../system/string/)) | 지정된 로컬 이름에 해당하는 네임스페이스 노드의 값을 반환합니다. |
| [SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IDictionary](../../system.collections.generic/idictionary/)\<[String](../../system/string/), [String](../../system/string/)\>\> [GetNamespacesInScope](./getnamespacesinscope/)([XmlNamespaceScope](../../system.xml/xmlnamespacescope/)) override | 현재 노드의 범위 내 네임스페이스를 반환합니다. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | 객체의 실제 유형을 가져옵니다. C# [System.Object.GetType()](../../system/object/gettype/) 호출과 유사합니다. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../../system.xml/xmlwriter/)\> [InsertAfter](./insertafter/)() | 현재 선택된 노드 뒤에 새 형제 노드를 만들 때 사용되는 [XmlWriter](../../system.xml/xmlwriter/) 객체를 반환합니다. |
| virtual void [InsertAfter](./insertafter/)([String](../../system/string/)) | 지정된 XML 문자열을 사용하여 현재 선택된 노드 뒤에 새 형제 노드를 생성합니다. |
| virtual void [InsertAfter](./insertafter/)([SharedPtr](../../system/sharedptr/)\<[XmlReader](../../system.xml/xmlreader/)\>) | 지정된 [XmlReader](../../system.xml/xmlreader/) 객체의 XML 내용을 사용하여 현재 선택된 노드 뒤에 새 형제 노드를 생성합니다. |
| virtual void [InsertAfter](./insertafter/)([SharedPtr](../../system/sharedptr/)\<[XPathNavigator](./)\>) | 지정된 [XPathNavigator](./) 객체의 노드를 사용하여 현재 선택된 노드 뒤에 새 형제 노드를 생성합니다. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../../system.xml/xmlwriter/)\> [InsertBefore](./insertbefore/)() | 현재 선택된 노드 앞에 새 형제 노드를 만들 때 사용되는 [XmlWriter](../../system.xml/xmlwriter/) 객체를 반환합니다. |
| virtual void [InsertBefore](./insertbefore/)([String](../../system/string/)) | 지정된 XML 문자열을 사용하여 현재 선택된 노드 앞에 새 형제 노드를 생성합니다. |
| virtual void [InsertBefore](./insertbefore/)([SharedPtr](../../system/sharedptr/)\<[XmlReader](../../system.xml/xmlreader/)\>) | 지정된 [XmlReader](../../system.xml/xmlreader/) 객체의 XML 내용을 사용하여 현재 선택된 노드 앞에 새 형제 노드를 생성합니다. |
| virtual void [InsertBefore](./insertbefore/)([SharedPtr](../../system/sharedptr/)\<[XPathNavigator](./)\>) | 지정된 [XPathNavigator](./)에 있는 노드를 사용하여 현재 선택된 노드 앞에 새 형제 노드를 생성합니다. |
| virtual void [InsertElementAfter](./insertelementafter/)([String](../../system/string/), [String](../../system/string/), [String](../../system/string/), [String](../../system/string/)) | 지정된 네임스페이스 접두사, 로컬 이름 및 네임스페이스 URI와 값을 사용하여 현재 노드 뒤에 새 형제 요소를 생성합니다. |
| virtual void [InsertElementBefore](./insertelementbefore/)([String](../../system/string/), [String](../../system/string/), [String](../../system/string/), [String](../../system/string/)) | 지정된 네임스페이스 접두사, 로컬 이름 및 네임스페이스 URI와 값을 사용하여 현재 노드 앞에 새 형제 요소를 생성합니다. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | 객체가 targetType이 설명하는 유형의 인스턴스를 나타내는지 확인합니다. C# 'is' 연산자와 유사합니다. |
| virtual **bool** [IsDescendant](./isdescendant/)([SharedPtr](../../system/sharedptr/)\<[XPathNavigator](./)\>) | 지정된 [XPathNavigator](./)가 현재 [XPathNavigator](./)의 하위 항목인지 여부를 결정합니다. |
| virtual **bool** [IsSamePosition](./issameposition/)([SharedPtr](../../system/sharedptr/)\<[XPathNavigator](./)\>) | 파생 클래스에서 재정의되면, 현재 [XPathNavigator](./)가 지정된 [XPathNavigator](./)와 동일한 위치에 있는지 여부를 결정합니다. |
| void [Lock](../../system/object/lock/)() | C# lock() 문을 구현합니다. 직접 호출하거나 [LockContext](../../system/lockcontext/) 감시자 객체를 사용합니다. |
| [String](../../system/string/) [LookupNamespace](./lookupnamespace/)(const [String](../../system/string/)\&) override | 지정된 접두사의 네임스페이스 URI를 반환합니다. |
| [String](../../system/string/) [LookupPrefix](./lookupprefix/)(const [String](../../system/string/)\&) override | 지정된 네임스페이스 URI에 선언된 접두사를 반환합니다. |
| virtual **bool** [Matches](./matches/)([SharedPtr](../../system/sharedptr/)\<[XPathExpression](../xpathexpression/)\>) | 현재 노드가 지정된 [XPathExpression](../xpathexpression/)와 일치하는지 여부를 결정합니다. |
| virtual **bool** [Matches](./matches/)([String](../../system/string/)) | 현재 노드가 지정된 [XPath](../) 식과 일치하는지 여부를 결정합니다. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) 메서드와 유사합니다. 사용자 정의 유형의 복제를 가능하게 합니다. |
| virtual **bool** [MoveTo](./moveto/)([SharedPtr](../../system/sharedptr/)\<[XPathNavigator](./)\>) | 파생 클래스에서 재정의되면, [XPathNavigator](./)를 지정된 [XPathNavigator](./)와 동일한 위치로 이동합니다. |
| virtual **bool** [MoveToAttribute](./movetoattribute/)([String](../../system/string/), [String](../../system/string/)) | [XPathNavigator](./)를 일치하는 로컬 이름 및 네임스페이스 URI를 가진 속성으로 이동합니다. |
| virtual **bool** [MoveToChild](./movetochild/)([String](../../system/string/), [String](../../system/string/)) | [XPathNavigator](./)를 지정된 로컬 이름 및 네임스페이스 URI를 가진 자식 노드로 이동합니다. |
| virtual **bool** [MoveToChild](./movetochild/)([XPathNodeType](../xpathnodetype/)) | [XPathNavigator](./)를 지정된 XPathNodeType의 자식 노드로 이동합니다. |
| virtual **bool** [MoveToFirst](./movetofirst/)() | [XPathNavigator](./)를 현재 노드의 첫 형제 노드로 이동합니다. |
| virtual **bool** [MoveToFirstAttribute](./movetofirstattribute/)() | 파생 클래스에서 재정의되면, [XPathNavigator](./)를 현재 노드의 첫 속성으로 이동합니다. |
| virtual **bool** [MoveToFirstChild](./movetofirstchild/)() | 파생 클래스에서 재정의되면, [XPathNavigator](./)를 현재 노드의 첫 자식 노드로 이동합니다. |
| virtual **bool** [MoveToFirstNamespace](./movetofirstnamespace/)([XPathNamespaceScope](../xpathnamespacescope/)) | 파생 클래스에서 재정의되면, [XPathNavigator](./)를 지정된 XPathNamespaceScope와 일치하는 첫 네임스페이스 노드로 이동합니다. |
| **bool** [MoveToFirstNamespace](./movetofirstnamespace/)() | [XPathNavigator](./)를 현재 노드의 첫 번째 네임스페이스 노드로 이동합니다. |
| virtual **bool** [MoveToFollowing](./movetofollowing/)([String](../../system/string/), [String](../../system/string/)) | [XPathNavigator](./)를 문서 순서에 지정된 로컬 이름과 네임스페이스 URI를 가진 요소로 이동합니다. |
| virtual **bool** [MoveToFollowing](./movetofollowing/)([String](../../system/string/), [String](../../system/string/), [SharedPtr](../../system/sharedptr/)\<[XPathNavigator](./)\>) | [XPathNavigator](./)를 문서 순서에서 지정된 경계까지, 지정된 로컬 이름과 네임스페이스 URI를 가진 요소로 이동합니다. |
| virtual **bool** [MoveToFollowing](./movetofollowing/)([XPathNodeType](../xpathnodetype/)) | [XPathNavigator](./)를 문서 순서에 지정된 XPathNodeType의 다음 요소로 이동합니다. |
| virtual **bool** [MoveToFollowing](./movetofollowing/)([XPathNodeType](../xpathnodetype/), [SharedPtr](../../system/sharedptr/)\<[XPathNavigator](./)\>) | [XPathNavigator](./)를 문서 순서에서 지정된 경계까지, 지정된 XPathNodeType의 다음 요소로 이동합니다. |
| virtual **bool** [MoveToId](./movetoid/)([String](../../system/string/)) | 파생 클래스에서 재정의될 경우, 지정된 [String](../../system/string/)와 값이 일치하는 **ID** 유형의 속성을 가진 노드로 이동합니다. |
| virtual **bool** [MoveToNamespace](./movetonamespace/)([String](../../system/string/)) | [XPathNavigator](./)를 지정된 네임스페이스 접두사를 가진 네임스페이스 노드로 이동합니다. |
| virtual **bool** [MoveToNext](./movetonext/)() | 파생 클래스에서 재정의될 경우, [XPathNavigator](./)를 현재 노드의 다음 형제 노드로 이동합니다. |
| virtual **bool** [MoveToNext](./movetonext/)([String](../../system/string/), [String](../../system/string/)) | [XPathNavigator](./)를 지정된 로컬 이름과 네임스페이스 URI를 가진 다음 형제 노드로 이동합니다. |
| virtual **bool** [MoveToNext](./movetonext/)([XPathNodeType](../xpathnodetype/)) | [XPathNavigator](./)를 지정된 XPathNodeType와 일치하는 현재 노드의 다음 형제 노드로 이동합니다. |
| virtual **bool** [MoveToNextAttribute](./movetonextattribute/)() | 파생 클래스에서 재정의될 경우, [XPathNavigator](./)를 다음 속성으로 이동합니다. |
| virtual **bool** [MoveToNextNamespace](./movetonextnamespace/)([XPathNamespaceScope](../xpathnamespacescope/)) | 파생 클래스에서 재정의될 경우, [XPathNavigator](./)를 지정된 XPathNamespaceScope와 일치하는 다음 네임스페이스 노드로 이동합니다. |
| **bool** [MoveToNextNamespace](./movetonextnamespace/)() | [XPathNavigator](./)를 다음 네임스페이스 노드로 이동합니다. |
| virtual **bool** [MoveToParent](./movetoparent/)() | 파생 클래스에서 재정의될 경우, [XPathNavigator](./)를 현재 노드의 부모 노드로 이동합니다. |
| virtual **bool** [MoveToPrevious](./movetoprevious/)() | 파생 클래스에서 재정의될 경우, [XPathNavigator](./)를 현재 노드의 이전 형제 노드로 이동합니다. |
| virtual void [MoveToRoot](./movetoroot/)() | [XPathNavigator](./)를 현재 노드가 속한 루트 노드로 이동합니다. |
|  [Object](../../system/object/object/)() | 객체를 생성합니다. 모든 내부 데이터 구조를 초기화합니다. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | 복사 생성자. 실제로 아무 것도 복사하지 않고, 새 객체를 초기화하고 하위 클래스의 복사 생성을 가능하게 합니다. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 대입 연산자. 실제로 아무 것도 복사하지 않고, 새 객체를 초기화하고 하위 클래스의 복사 생성을 가능하게 합니다. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../../system.xml/xmlwriter/)\> [PrependChild](./prependchild/)() | 현재 노드의 자식 노드 목록 시작에 새 자식 노드를 생성하는 데 사용되는 [XmlWriter](../../system.xml/xmlwriter/) 객체를 반환합니다. |
| virtual void [PrependChild](./prependchild/)([String](../../system/string/)) | 지정된 XML 문자열을 사용하여 현재 노드의 자식 노드 목록 시작에 새로운 자식 노드를 생성합니다. |
| virtual void [PrependChild](./prependchild/)([SharedPtr](../../system/sharedptr/)\<[XmlReader](../../system.xml/xmlreader/)\>) | 지정된 [XmlReader](../../system.xml/xmlreader/) 객체의 XML 내용을 사용하여 현재 노드의 자식 노드 목록 시작에 새로운 자식 노드를 생성합니다. |
| virtual void [PrependChild](./prependchild/)([SharedPtr](../../system/sharedptr/)\<[XPathNavigator](./)\>) | 지정된 [XPathNavigator](./) 객체의 노드를 사용하여 현재 노드의 자식 노드 목록 시작에 새로운 자식 노드를 생성합니다. |
| virtual void [PrependChildElement](./prependchildelement/)([String](../../system/string/), [String](../../system/string/), [String](../../system/string/), [String](../../system/string/)) | 지정된 값과 함께 지정된 네임스페이스 접두사, 로컬 이름, 네임스페이스 URI를 사용하여 현재 노드의 자식 노드 목록 시작에 새로운 자식 요소를 생성합니다. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlReader](../../system.xml/xmlreader/)\> [ReadSubtree](./readsubtree/)() | 현재 노드와 그 자식 노드를 포함하는 [XmlReader](../../system.xml/xmlreader/) 객체를 반환합니다. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 객체를 참조 기준으로 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 객체를 참조 기준으로 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 값 형식 객체를 nullptr와 참조 비교합니다. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | 문자열과 nullptr 경우에 대한 [Object::ReferenceEquals](../../system/object/referenceequals/) 특수화입니다. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | 문자열 경우에 대한 [Object::ReferenceEquals](../../system/object/referenceequals/) 특수화입니다. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 지정된 값만큼 공유 참조 카운트를 감소시킵니다. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../../system.xml/xmlwriter/)\> [ReplaceRange](./replacerange/)([SharedPtr](../../system/sharedptr/)\<[XPathNavigator](./)\>) | 현재 노드부터 지정된 노드까지 형제 노드 범위를 교체합니다. |
| virtual void [ReplaceSelf](./replaceself/)([String](../../system/string/)) | 현재 노드를 지정된 문자열 내용으로 교체합니다. |
| virtual void [ReplaceSelf](./replaceself/)([SharedPtr](../../system/sharedptr/)\<[XmlReader](../../system.xml/xmlreader/)\>) | 현재 노드를 지정된 [XmlReader](../../system.xml/xmlreader/) 객체의 내용으로 교체합니다. |
| virtual void [ReplaceSelf](./replaceself/)([SharedPtr](../../system/sharedptr/)\<[XPathNavigator](./)\>) | 현재 노드를 지정된 [XPathNavigator](./) 객체의 내용으로 교체합니다. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XPathNodeIterator](../xpathnodeiterator/)\> [Select](./select/)([String](../../system/string/)) | 지정된 [XPath](../) 표현식을 사용하여 노드 집합을 선택합니다. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XPathNodeIterator](../xpathnodeiterator/)\> [Select](./select/)([String](../../system/string/), [SharedPtr](../../system/sharedptr/)\<[IXmlNamespaceResolver](../../system.xml/ixmlnamespaceresolver/)\>) | 지정된 [IXmlNamespaceResolver](../../system.xml/ixmlnamespaceresolver/) 객체를 사용하여 네임스페이스 접두사를 해결하고, 지정된 [XPath](../) 표현식을 사용하여 노드 집합을 선택합니다. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XPathNodeIterator](../xpathnodeiterator/)\> [Select](./select/)([SharedPtr](../../system/sharedptr/)\<[XPathExpression](../xpathexpression/)\>) | 지정된 [XPathExpression](../xpathexpression/)를 사용하여 노드 집합을 선택합니다. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XPathNodeIterator](../xpathnodeiterator/)\> [SelectAncestors](./selectancestors/)([XPathNodeType](../xpathnodetype/), **bool**) | 일치하는 XPathNodeType을 가진 현재 노드의 모든 선조 노드를 선택합니다. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XPathNodeIterator](../xpathnodeiterator/)\> [SelectAncestors](./selectancestors/)([String](../../system/string/), [String](../../system/string/), **bool**) | 지정된 로컬 이름과 네임스페이스 URI를 가진 현재 노드의 모든 선조 노드를 선택합니다. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XPathNodeIterator](../xpathnodeiterator/)\> [SelectChildren](./selectchildren/)([XPathNodeType](../xpathnodetype/)) | 일치하는 XPathNodeType을 가진 현재 노드의 모든 자식 노드를 선택합니다. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XPathNodeIterator](../xpathnodeiterator/)\> [SelectChildren](./selectchildren/)([String](../../system/string/), [String](../../system/string/)) | 지정된 로컬 이름과 네임스페이스 URI를 가진 현재 노드의 모든 자식 노드를 선택합니다. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XPathNodeIterator](../xpathnodeiterator/)\> [SelectDescendants](./selectdescendants/)([XPathNodeType](../xpathnodetype/), **bool**) | 일치하는 XPathNodeType을 가진 현재 노드의 모든 하위 노드를 선택합니다. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XPathNodeIterator](../xpathnodeiterator/)\> [SelectDescendants](./selectdescendants/)([String](../../system/string/), [String](../../system/string/), **bool**) | 지정된 로컬 이름과 네임스페이스 URI를 가진 현재 노드의 모든 하위 노드를 선택합니다. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XPathNavigator](./)\> [SelectSingleNode](./selectsinglenode/)([String](../../system/string/)) | 지정된 [XPath](../) 쿼리를 사용하여 [XPathNavigator](./)에서 단일 노드를 선택합니다. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XPathNavigator](./)\> [SelectSingleNode](./selectsinglenode/)([String](../../system/string/), [SharedPtr](../../system/sharedptr/)\<[IXmlNamespaceResolver](../../system.xml/ixmlnamespaceresolver/)\>) | 네임스페이스 접두사를 해결하기 위해 지정된 [IXmlNamespaceResolver](../../system.xml/ixmlnamespaceresolver/) 객체를 사용하고, 지정된 [XPath](../) 쿼리를 이용하여 [XPathNavigator](./) 객체에서 단일 노드를 선택합니다. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XPathNavigator](./)\> [SelectSingleNode](./selectsinglenode/)([SharedPtr](../../system/sharedptr/)\<[XPathExpression](../xpathexpression/)\>) | 지정된 [XPathExpression](../xpathexpression/) 객체를 사용하여 [XPathNavigator](./)에서 단일 노드를 선택합니다. |
| virtual void [set_InnerXml](./set_innerxml/)([String](../../system/string/)) | 현재 노드의 자식 노드를 나타내는 마크업을 설정합니다. |
| virtual void [set_OuterXml](./set_outerxml/)([String](../../system/string/)) | 현재 노드와 그 자식 노드의 시작 및 종료 태그를 나타내는 마크업을 설정합니다. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n번째 템플릿 인자를 약한 포인터(공유 대신)로 설정합니다. 컨테이너에서 포인터를 약한 모드로 전환할 수 있습니다. |
| virtual void [SetTypedValue](./settypedvalue/)([SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) | 현재 노드의 타입 지정 값을 설정합니다. |
| virtual void [SetValue](./setvalue/)([String](../../system/string/)) | 현재 노드의 값을 설정합니다. |
| int [SharedCount](../../system/object/sharedcount/)() const | 공유 참조 카운터의 현재 값을 가져옵니다. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 공유 참조 카운트를 증가시킵니다. 직접 호출해서는 안 되며, 대신 스마트 포인터 또는 ThisProtector를 사용하십시오. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 공유 참조 카운트를 감소시키고 반환합니다. 직접 호출해서는 안 되며, 대신 스마트 포인터 또는 ThisProtector를 사용하십시오. |
| [String](../../system/string/) [ToString](./tostring/)() const override | 현재 노드의 텍스트 값을 반환합니다. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) 구성을 구현합니다. |
| void [Unlock](../../system/object/unlock/)() | C# lock() 문 잠금 해제를 구현합니다. 직접 호출하거나 [LockContext](../../system/lockcontext/) 감시 객체를 사용하십시오. |
| [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ValueAs](./valueas/)(const [TypeInfo](../../system/typeinfo/)\&, [SharedPtr](../../system/sharedptr/)\<[IXmlNamespaceResolver](../../system.xml/ixmlnamespaceresolver/)\>) override | 네임스페이스 접두사를 해결하기 위해 지정된 [IXmlNamespaceResolver](../../system.xml/ixmlnamespaceresolver/) 객체를 사용하여 지정된 Type으로 현재 노드의 값을 반환합니다. |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ValueAs](../xpathitem/valueas/)(const [TypeInfo](../../system/typeinfo/)\&) | 항목의 값을 지정된 타입으로 반환합니다. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 약한 참조 카운트를 증가시킵니다. 직접 호출해서는 안 되며, 대신 스마트 포인터 또는 ThisProtector를 사용하십시오. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 약한 참조 카운트를 감소시킵니다. 직접 호출해서는 안 되며, 대신 스마트 포인터 또는 ThisProtector를 사용하십시오. |
| virtual void [WriteSubtree](./writesubtree/)([SharedPtr](../../system/sharedptr/)\<[XmlWriter](../../system.xml/xmlwriter/)\>) | 현재 노드와 그 자식 노드를 지정된 [XmlWriter](../../system.xml/xmlwriter/) 객체로 스트리밍합니다. |
| virtual  [~Object](../../system/object/~object/)() | 객체를 파괴합니다. 모든 내부 데이터 구조를 해제합니다. |

## 타입 정의

| 타입 정의 | 설명 |
| --- | --- |
| [Ptr](./ptr/) | 이 클래스의 인스턴스에 대한 공유 포인터 별칭입니다. |

## 참고

* 클래스 [XPathItem](../xpathitem/)
* 클래스 [IXPathNavigable](../ixpathnavigable/)
* 클래스 [IXmlNamespaceResolver](../../system.xml/ixmlnamespaceresolver/)
* 네임스페이스 [System::Xml::XPath](../)
* 라이브러리 [Aspose.Slides](../../)