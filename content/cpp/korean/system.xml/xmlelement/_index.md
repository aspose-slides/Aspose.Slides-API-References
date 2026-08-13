---
title: XmlElement
second_title: Aspose.Slides for C++ API 레퍼런스
description: 요소를 나타냅니다.
type: docs
weight: 222
url: /ko/system.xml/xmlelement/
---
## XmlElement 클래스

요소를 나타냅니다.

```cpp
class XmlElement : public System::Xml::XmlLinkedNode
```

## 메서드

| Method | Description |
| --- | --- |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\> [AppendChild](../xmlnode/appendchild/)([SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\>) | 지정된 노드를 이 노드의 자식 노드 목록 끝에 추가합니다. |
| [iterator](../../system.collections.generic/ienumerable/iterator/) [begin](../../system.collections.generic/ienumerable/begin/)() | 컬렉션의 첫 번째 요소(있는 경우)를 가리키는 반복자를 가져옵니다. 이 반복자는 [GetEnumerator()](../../system.collections.generic/ienumerable/getenumerator/)가 T의 복사 객체를 반환하기 때문에 참조된 객체를 변경하는 데 사용할 수 없습니다. |
| [const_iterator](../../system.collections.generic/ienumerable/const_iterator/) [begin](../../system.collections.generic/ienumerable/begin/)() const | 컬렉션의 const 한정 인스턴스에서 첫 번째 요소(있는 경우)를 가리키는 반복자를 가져옵니다. |
| [const_iterator](../../system.collections.generic/ienumerable/const_iterator/) [cbegin](../../system.collections.generic/ienumerable/cbegin/)() const | 컬렉션에서 첫 번째 const 한정 요소(있는 경우)를 가리키는 반복자를 가져옵니다. |
| [const_iterator](../../system.collections.generic/ienumerable/const_iterator/) [cend](../../system.collections.generic/ienumerable/cend/)() const | 컬렉션에서 마지막 const 한정 요소(있는 경우) 바로 다음을 가리키는 반복자를 가져옵니다. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\> [Clone](../xmlnode/clone/)() | 이 노드의 복제본을 생성합니다. |
| [SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\> [CloneNode](./clonenode/)(**bool**) override | 이 노드의 복제본을 생성합니다. |
| [SharedPtr](../../system/sharedptr/)\<[XPath::XPathNavigator](../../system.xml.xpath/xpathnavigator/)\> [CreateNavigator](../xmlnode/createnavigator/)() override | 이 객체를 탐색하기 위한 XPathNavigator를 생성합니다. |
| [iterator](../../system.collections.generic/ienumerable/iterator/) [end](../../system.collections.generic/ienumerable/end/)() | 컬렉션에서 마지막 요소(있는 경우) 바로 다음을 가리키는 반복자를 가져옵니다. 이 반복자는 [GetEnumerator()](../../system.collections.generic/ienumerable/getenumerator/)가 T의 복사 객체를 반환하기 때문에 참조된 객체를 변경하는 데 사용할 수 없습니다. |
| [const_iterator](../../system.collections.generic/ienumerable/const_iterator/) [end](../../system.collections.generic/ienumerable/end/)() const | const 한정된 컬렉션 인스턴스에서 마지막 요소(있는 경우) 바로 다음을 가리키는 반복자를 가져옵니다. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) 의미에 따라 객체를 비교합니다. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# 스타일로 참조 형식 객체를 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# 스타일로 값 형식 객체를 비교합니다. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | IEC 60559:1989에 따르면 NaN은 어떤 값과도 같지 않지만, 두 NaN을 동일하게 간주하는 C# 스타일 부동소수점 비교를 에뮬레이트합니다. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | IEC 60559:1989에 따르면 NaN은 어떤 값과도 같지 않지만, 두 NaN을 동일하게 간주하는 C# 스타일 부동소수점 비교를 에뮬레이트합니다. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 내부 용도로만 사용됩니다. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlAttributeCollection](../xmlattributecollection/)\> [get_Attributes](../xmlnode/get_attributes/)() | 이 노드의 속성을 포함하는 [XmlAttributeCollection](../xmlattributecollection/)를 반환합니다. |
| virtual [String](../../system/string/) [get_BaseURI](../xmlnode/get_baseuri/)() | 현재 노드의 기본 URI를 반환합니다. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlNodeList](../xmlnodelist/)\> [get_ChildNodes](../xmlnode/get_childnodes/)() | 노드의 모든 자식 노드를 반환합니다. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\> [get_FirstChild](../xmlnode/get_firstchild/)() | 노드의 첫 번째 자식을 반환합니다. |
| virtual **bool** [get_HasAttributes](./get_hasattributes/)() | 현재 노드에 속성이 있는지 여부를 나타내는 **bool** 값을 반환합니다. |
| virtual **bool** [get_HasChildNodes](../xmlnode/get_haschildnodes/)() | 이 노드에 자식 노드가 있는지 여부를 나타내는 값을 반환합니다. |
| [String](../../system/string/) [get_InnerText](./get_innertext/)() override | 노드와 모든 자식의 값을 연결하여 반환합니다. |
| [String](../../system/string/) [get_InnerXml](./get_innerxml/)() override | 이 노드의 자식만을 나타내는 마크업을 반환합니다. |
| **bool** [get_IsEmpty](./get_isempty/)() | 요소의 태그 형식을 반환합니다. |
| virtual **bool** [get_IsReadOnly](../xmlnode/get_isreadonly/)() | 노드가 읽기 전용인지 여부를 나타내는 값을 반환합니다. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\> [get_LastChild](../xmlnode/get_lastchild/)() | 노드의 마지막 자식을 반환합니다. |
| [String](../../system/string/) [get_LocalName](./get_localname/)() override | 현재 노드의 로컬 이름을 반환합니다. |
| [String](../../system/string/) [get_Name](./get_name/)() override | 노드의 정규화된 이름을 반환합니다. |
| [String](../../system/string/) [get_NamespaceURI](./get_namespaceuri/)() override | 이 노드의 네임스페이스 URI를 반환합니다. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\> [get_NextSibling](../xmlnode/get_nextsibling/)() | 이 노드 바로 다음의 노드를 반환합니다. |
| [XmlNodeType](../xmlnodetype/) [get_NodeType](./get_nodetype/)() override | 현재 노드의 유형을 반환합니다. |
| virtual [String](../../system/string/) [get_OuterXml](../xmlnode/get_outerxml/)() | 이 노드와 모든 자식 노드를 포함하는 마크업을 반환합니다. |
| [SharedPtr](../../system/sharedptr/)\<[XmlDocument](../xmldocument/)\> [get_OwnerDocument](./get_ownerdocument/)() override | 이 노드가 속한 [XmlDocument](../xmldocument/)를 반환합니다. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\> [get_ParentNode](../xmlnode/get_parentnode/)() | 이 노드의 부모를 반환합니다(부모를 가질 수 있는 노드에 대해). |
| [String](../../system/string/) [get_Prefix](./get_prefix/)() override | 이 노드의 네임스페이스 접두사를 반환합니다. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\> [get_PreviousSibling](../xmlnode/get_previoussibling/)() | 이 노드 바로 이전의 노드를 반환합니다. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\> [get_PreviousText](../xmlnode/get_previoustext/)() | 이 노드 바로 앞에 있는 텍스트 노드를 반환합니다. |
| [SharedPtr](../../system/sharedptr/)\<[Schema::IXmlSchemaInfo](../../system.xml.schema/ixmlschemainfo/)\> [get_SchemaInfo](./get_schemainfo/)() override | 스키마 검증 결과로 이 노드에 할당된 사후 스키마 검증 정보 세트를 반환합니다. |
| virtual [String](../../system/string/) [get_Value](../xmlnode/get_value/)() | 노드의 값을 반환합니다. |
| virtual [String](../../system/string/) [GetAttribute](./getattribute/)([String](../../system/string/)) | 지정된 이름을 가진 속성의 값을 반환합니다. |
| virtual [String](../../system/string/) [GetAttribute](./getattribute/)([String](../../system/string/), [String](../../system/string/)) | 지정된 로컬 이름과 네임스페이스 URI를 가진 속성의 값을 반환합니다. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlAttribute](../xmlattribute/)\> [GetAttributeNode](./getattributenode/)([String](../../system/string/)) | 지정된 이름을 가진 [XmlAttribute](../xmlattribute/)를 반환합니다. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlAttribute](../xmlattribute/)\> [GetAttributeNode](./getattributenode/)([String](../../system/string/), [String](../../system/string/)) | 지정된 로컬 이름과 네임스페이스 URI를 가진 [XmlAttribute](../xmlattribute/)를 반환합니다. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | 객체와 연결된 참조 카운터 데이터 구조를 가져옵니다. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlNodeList](../xmlnodelist/)\> [GetElementsByTagName](./getelementsbytagname/)([String](../../system/string/)) | 지정된 [XmlElement::get_Name](./get_name/)와 일치하는 모든 하위 요소 목록을 포함하는 [XmlNodeList](../xmlnodelist/)를 반환합니다. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlNodeList](../xmlnodelist/)\> [GetElementsByTagName](./getelementsbytagname/)([String](../../system/string/), [String](../../system/string/)) | 지정된 [XmlElement::get_LocalName](./get_localname/) 및 [XmlElement::get_NamespaceURI](./get_namespaceuri/) 값과 일치하는 모든 하위 요소 목록을 포함하는 [XmlNodeList](../xmlnodelist/)를 반환합니다. |
| [SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IEnumerator](../../system.collections.generic/ienumerator/)\<[SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\>\>\> [GetEnumerator](../xmlnode/getenumerator/)() override | 현재 노드의 자식 노드를 순회하는 열거자를 반환합니다. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) 메서드와 유사합니다. 사용자 정의 객체의 해싱을 가능하게 합니다. |
| virtual [String](../../system/string/) [GetNamespaceOfPrefix](../xmlnode/getnamespaceofprefix/)([String](../../system/string/)) | 현재 노드 범위에 있는 지정된 접두사에 가장 가까운 **xmlns** 선언을 찾아 해당 선언의 네임스페이스 URI를 반환합니다. |
| virtual [String](../../system/string/) [GetPrefixOfNamespace](../xmlnode/getprefixofnamespace/)([String](../../system/string/)) | 현재 노드 범위에 있는 지정된 네임스페이스 URI에 가장 가까운 **xmlns** 선언을 찾아 해당 선언에 정의된 접두사를 반환합니다. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | 객체의 실제 유형을 가져옵니다. C# [System.Object.GetType()](../../system/object/gettype/) 호출과 유사합니다. |
| virtual **bool** [HasAttribute](./hasattribute/)([String](../../system/string/)) | 현재 노드에 지정된 이름을 가진 속성이 있는지 여부를 판단합니다. |
| virtual **bool** [HasAttribute](./hasattribute/)([String](../../system/string/), [String](../../system/string/)) | 현재 노드에 지정된 로컬 이름과 네임스페이스 URI를 가진 속성이 있는지 여부를 판단합니다. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlElement](./)\> [idx_get](../xmlnode/idx_get/)([String](../../system/string/)) | 지정된 [XmlNode::get_Name](../xmlnode/get_name/)를 가진 첫 번째 자식 요소를 반환합니다. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlElement](./)\> [idx_get](../xmlnode/idx_get/)([String](../../system/string/), [String](../../system/string/)) | 지정된 [XmlNode::get_LocalName](../xmlnode/get_localname/) 및 [XmlNode::get_NamespaceURI](../xmlnode/get_namespaceuri/) 값을 가진 첫 번째 자식 요소를 반환합니다. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\> [InsertAfter](../xmlnode/insertafter/)([SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\>, [SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\>) | 지정된 참조 노드 바로 뒤에 지정된 노드를 삽입합니다. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\> [InsertBefore](../xmlnode/insertbefore/)([SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\>, [SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\>) | 지정된 참조 노드 바로 앞에 지정된 노드를 삽입합니다. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | 객체가 targetType에 의해 설명된 유형의 인스턴스를 나타내는지 확인합니다. C# 'is' 연산자와 유사합니다. |
| T [LINQ_Aggregate](../../system.collections.generic/ienumerable/linq_aggregate/)(const [Func](../../system/func/)\<T, T, T\>\&) | 시퀀스에 누산기 함수를 적용합니다. |
| **bool** [LINQ_All](../../system.collections.generic/ienumerable/linq_all/)(std::function\<**bool**(T)>) | 시퀀스의 모든 요소가 조건을 만족하는지 여부를 판단합니다. |
| **bool** [LINQ_Any](../../system.collections.generic/ienumerable/linq_any/)() | 시퀀스에 요소가 있는지 여부를 판단합니다. |
| **bool** [LINQ_Any](../../system.collections.generic/ienumerable/linq_any/)(std::function\<**bool**(T)>) | 시퀀스에 요소가 존재하거나 조건을 만족하는지 여부를 판단합니다. |
| T [LINQ_Average](../../system.collections.generic/ienumerable/linq_average/)() | 숫자 값 시퀀스의 평균을 계산합니다. |
| ResultType [LINQ_Average](../../system.collections.generic/ienumerable/linq_average/)(const [Func](../../system/func/)\<T, ResultType\>\&) | 입력 시퀀스의 각 요소에 변환 함수를 호출하여 얻은 값들의 평균을 계산합니다. |
| ResultType [LINQ_Average](../../system.collections.generic/ienumerable/linq_average/)(const [Func](../../system/func/)\<Source, ResultType\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_Cast](../../system.collections.generic/ienumerable/linq_cast/)() | 요소를 지정된 타입으로 캐스팅합니다. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_Cast](../../system.collections.generic/ienumerable/linq_cast/)() |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Concat](../../system.collections.generic/ienumerable/linq_concat/)([SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\>) | 두 개의 시퀀스를 연결합니다. |
| **bool** [LINQ_Contains](../../system.collections.generic/ienumerable/linq_contains/)(T) | 시퀀스에 지정된 값이 포함되는지 여부를 판단합니다. |
| int [LINQ_Count](../../system.collections.generic/ienumerable/linq_count/)() | 시퀀스의 요소 개수를 반환합니다(직접 계산). |
| int [LINQ_Count](../../system.collections.generic/ienumerable/linq_count/)(const [Func](../../system/func/)\<T, **bool**\>\&) | 지정된 조건을 만족하는 시퀀스 요소의 개수를 반환합니다. |
| T [LINQ_ElementAt](../../system.collections.generic/ienumerable/linq_elementat/)(int) | 시퀀스에서 지정된 인덱스의 요소를 반환합니다. |
| T [LINQ_ElementAtOrDefault](../../system.collections.generic/ienumerable/linq_elementatordefault/)(int) | 시퀀스에서 지정된 인덱스의 요소를 반환합니다. |
| T [LINQ_First](../../system.collections.generic/ienumerable/linq_first/)() | 시퀀스의 첫 번째 요소를 반환합니다. |
| T [LINQ_First](../../system.collections.generic/ienumerable/linq_first/)(const [Func](../../system/func/)\<T, **bool**\>\&) | 지정된 조건을 만족하는 시퀀스의 첫 번째 요소를 반환합니다. |
| T [LINQ_FirstOrDefault](../../system.collections.generic/ienumerable/linq_firstordefault/)() | 시퀀스의 첫 번째 요소를 반환하며, 시퀀스가 비어 있으면 기본값을 반환합니다. |
| T [LINQ_FirstOrDefault](../../system.collections.generic/ienumerable/linq_firstordefault/)(std::function\<**bool**(T)>) | 조건을 만족하는 시퀀스의 첫 번째 요소를 반환하며, 해당 요소가 없으면 기본값을 반환합니다. |
| [System::SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[System::SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, T\>\>\>\> [LINQ_GroupBy](../../system.collections.generic/ienumerable/linq_groupby/)([System::Func](../../system/func/)\<T, Key\>) | 시퀀스의 요소들을 그룹화합니다. |
| [System::SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[System::SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Element\>\>\>\> [LINQ_GroupBy](../../system.collections.generic/ienumerable/linq_groupby/)([System::Func](../../system/func/)\<T, Key\>, [System::Func](../../system/func/)\<T, Element\>) | 시퀀스의 요소들을 그룹화합니다. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Source\>\>\>\> [LINQ_GroupBy](../../system.collections.generic/ienumerable/linq_groupby/)([System::Func](../../system/func/)\<Source, Key\>) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Element\>\>\>\> [LINQ_GroupBy](../../system.collections.generic/ienumerable/linq_groupby/)([System::Func](../../system/func/)\<Source, Key\>, [System::Func](../../system/func/)\<Source, Element\>) |  |
| T [LINQ_Last](../../system.collections.generic/ienumerable/linq_last/)() | 시퀀스의 마지막 요소를 반환합니다. |
| T [LINQ_LastOrDefault](../../system.collections.generic/ienumerable/linq_lastordefault/)() | 시퀀스의 마지막 요소를 반환하며, 시퀀스가 비어 있으면 기본값을 반환합니다. |
| ResultType [LINQ_Max](../../system.collections.generic/ienumerable/linq_max/)(const [Func](../../system/func/)\<T, ResultType\>\&) | 일반 시퀀스의 각 요소에 변환 함수를 호출하고 최대 결과값을 반환합니다. |
| ResultType [LINQ_Max](../../system.collections.generic/ienumerable/linq_max/)(const [Func](../../system/func/)\<Source, ResultType\>\&) |  |
| ResultType [LINQ_Min](../../system.collections.generic/ienumerable/linq_min/)(const [Func](../../system/func/)\<T, ResultType\>\&) | 일반 시퀀스의 각 요소에 변환 함수를 호출하고 최소 결과값을 반환합니다. |
| ResultType [LINQ_Min](../../system.collections.generic/ienumerable/linq_min/)(const [Func](../../system/func/)\<Source, ResultType\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_OfType](../../system.collections.generic/ienumerable/linq_oftype/)() | 지정된 타입을 기준으로 시퀀스의 요소를 필터링합니다. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_OfType](../../system.collections.generic/ienumerable/linq_oftype/)() |  |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<T\>\> [LINQ_OrderBy](../../system.collections.generic/ienumerable/linq_orderby/)(const [Func](../../system/func/)\<T, Key\>\&) | keySelector가 선택한 키 값을 기준으로 시퀀스의 요소를 오름차순으로 정렬합니다. |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<Source\>\> [LINQ_OrderBy](../../system.collections.generic/ienumerable/linq_orderby/)(const [Func](../../system/func/)\<Source, Key\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<T\>\> [LINQ_OrderByDescending](../../system.collections.generic/ienumerable/linq_orderbydescending/)(const [Func](../../system/func/)\<T, Key\>\&) | keySelector가 선택한 키 값을 기준으로 시퀀스의 요소를 내림차순으로 정렬합니다. |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<Source\>\> [LINQ_OrderByDescending](../../system.collections.generic/ienumerable/linq_orderbydescending/)(const [Func](../../system/func/)\<Source, Key\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Reverse](../../system.collections.generic/ienumerable/linq_reverse/)() | 시퀀스의 요소 순서를 뒤집습니다. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_Select](../../system.collections.generic/ienumerable/linq_select/)(const [Func](../../system/func/)\<T, ResultType\>\&) | 시퀀스의 요소를 변환합니다. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_Select](../../system.collections.generic/ienumerable/linq_select/)(const [Func](../../system/func/)\<T, **int32_t**, ResultType\>\&) | 요소의 인덱스를 포함시켜 시퀀스의 각 요소를 새로운 형태로 변환합니다. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_Select](../../system.collections.generic/ienumerable/linq_select/)(const [Func](../../system/func/)\<Source, Result\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_Select](../../system.collections.generic/ienumerable/linq_select/)(const [Func](../../system/func/)\<Source, **int32_t**, Result\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_SelectMany](../../system.collections.generic/ienumerable/linq_selectmany/)(const [Func](../../system/func/)\<T, [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\>\>\&) | 시퀀스의 각 요소를 프로젝션하고 결과 시퀀스를 하나의 시퀀스로 결합합니다. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_SelectMany](../../system.collections.generic/ienumerable/linq_selectmany/)(const [Func](../../system/func/)\<Source, [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\>\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Skip](../../system.collections.generic/ienumerable/linq_skip/)(**int32_t**) | 시퀀스의 시작에서 연속된 지정된 수의 요소를 건너뛰고 나머지를 반환합니다. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Take](../../system.collections.generic/ienumerable/linq_take/)(**int32_t**) | 시퀀스 시작부터 지정된 수의 연속된 요소들을 반환합니다. |
| [System::ArrayPtr](../../system/arrayptr/)\<T\> [LINQ_ToArray](../../system.collections.generic/ienumerable/linq_toarray/)() | 시퀀스로부터 배열을 생성합니다. |
| [SharedPtr](../../system/sharedptr/)\<[List](../../system.collections.generic/list/)\<T\>\> [LINQ_ToList](../../system.collections.generic/ienumerable/linq_tolist/)() | 시퀀스로부터 List<T>를 생성합니다. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Where](../../system.collections.generic/ienumerable/linq_where/)(std::function\<**bool**(T)>) | 지정된 조건(predicate)을 기준으로 시퀀스를 필터링합니다. |
| void [Lock](../../system/object/lock/)() | C# lock() 구문의 잠금을 구현합니다. 직접 호출하거나 [LockContext](../../system/lockcontext/) 감시 객체를 사용합니다. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) 메서드의 유사체입니다. 사용자 정의 형식 복제를 가능하게 합니다. |
| virtual void [Normalize](../xmlnode/normalize/)() | 이 [XmlNode](../xmlnode/) 아래의 서브 트리 전체 깊이에 있는 모든 [XmlText](../xmltext/) 노드를 마크업(즉, 태그, 주석, 처리 지시문, CDATA 섹션 및 엔티티 참조)만이 [XmlText](../xmltext/) 노드들을 구분하도록 "정상" 형태로 변환합니다. 즉, 인접한 [XmlText](../xmltext/) 노드가 없게 됩니다. |
|  [Object](../../system/object/object/)() | 객체를 생성합니다. 모든 내부 데이터 구조를 초기화합니다. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | 복사 생성자. 실제로는 아무것도 복사하지 않고, 새 객체를 초기화하며 서브클래스의 복사 생성을 가능하게 합니다. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 대입 연산자. 실제로는 아무것도 복사하지 않고, 새 객체를 초기화하며 서브클래스의 복사 생성을 가능하게 합니다. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\> [PrependChild](../xmlnode/prependchild/)([SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\>) | 지정된 노드를 이 노드의 자식 노드 리스트 앞에 추가합니다. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 객체를 참조 기준으로 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 객체를 참조 기준으로 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 값 형식 객체를 nullptr와 참조 비교합니다. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | 문자열과 nullptr 경우에 대한 [Object::ReferenceEquals](../../system/object/referenceequals/) 특수화입니다. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | 문자열 경우에 대한 [Object::ReferenceEquals](../../system/object/referenceequals/) 특수화입니다. |
| void [RemoveAll](./removeall/)() override | 현재 노드의 지정된 모든 속성과 자식 노드를 제거합니다. 기본 속성은 제거되지 않습니다. |
| virtual void [RemoveAllAttributes](./removeallattributes/)() | 요소에서 지정된 모든 속성을 제거합니다. 기본 속성은 제거되지 않습니다. |
| virtual void [RemoveAttribute](./removeattribute/)([String](../../system/string/)) | 이름으로 속성을 제거합니다. |
| virtual void [RemoveAttribute](./removeattribute/)([String](../../system/string/), [String](../../system/string/)) | 지정된 로컬 이름과 네임스페이스 URI를 가진 속성을 제거합니다. (제거된 속성에 기본값이 있는 경우 즉시 교체됩니다.) |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\> [RemoveAttributeAt](./removeattributeat/)(**int32_t**) | 요소에서 지정된 인덱스의 속성 노드를 제거합니다. (제거된 속성에 기본값이 있는 경우 즉시 교체됩니다.) |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlAttribute](../xmlattribute/)\> [RemoveAttributeNode](./removeattributenode/)([SharedPtr](../../system/sharedptr/)\<[XmlAttribute](../xmlattribute/)\>) | 지정된 [XmlAttribute](../xmlattribute/)를 제거합니다. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlAttribute](../xmlattribute/)\> [RemoveAttributeNode](./removeattributenode/)([String](../../system/string/), [String](../../system/string/)) | 로컬 이름과 네임스페이스 URI로 지정된 [XmlAttribute](../xmlattribute/)를 제거합니다. (제거된 속성에 기본값이 있는 경우 즉시 교체됩니다.) |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\> [RemoveChild](../xmlnode/removechild/)([SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\>) | 지정된 자식 노드를 제거합니다. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 지정된 값만큼 공유 참조 카운트를 감소시킵니다. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\> [ReplaceChild](../xmlnode/replacechild/)([SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\>, [SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\>) | 자식 노드 **oldChild**를 **newChild** 노드로 교체합니다. |
| [SharedPtr](../../system/sharedptr/)\<[XmlNodeList](../xmlnodelist/)\> [SelectNodes](../xmlnode/selectnodes/)(const [String](../../system/string/)\&) | [XPath](../../system.xml.xpath/) 표현식과 일치하는 노드 목록을 선택합니다. |
| [SharedPtr](../../system/sharedptr/)\<[XmlNodeList](../xmlnodelist/)\> [SelectNodes](../xmlnode/selectnodes/)(const [String](../../system/string/)\&, const [SharedPtr](../../system/sharedptr/)\<[XmlNamespaceManager](../xmlnamespacemanager/)\>\&) | [XPath](../../system.xml.xpath/) 표현식과 일치하는 노드 목록을 선택합니다. [XPath](../../system.xml.xpath/) 표현식에서 발견된 모든 접두사는 제공된 [XmlNamespaceManager](../xmlnamespacemanager/)을 사용해 해석됩니다. |
| [SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\> [SelectSingleNode](../xmlnode/selectsinglenode/)(const [String](../../system/string/)\&) | [XPath](../../system.xml.xpath/) 표현식과 일치하는 첫 번째 [XmlNode](../xmlnode/)를 선택합니다. |
| [SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\> [SelectSingleNode](../xmlnode/selectsinglenode/)(const [String](../../system/string/)\&, const [SharedPtr](../../system/sharedptr/)\<[XmlNamespaceManager](../xmlnamespacemanager/)\>\&) | [XPath](../../system.xml.xpath/) 표현식과 일치하는 첫 번째 [XmlNode](../xmlnode/)를 선택합니다. [XPath](../../system.xml.xpath/) 표현식에서 발견된 모든 접두사는 제공된 [XmlNamespaceManager](../xmlnamespacemanager/)을 사용해 해석됩니다. |
| void [set_InnerText](./set_innertext/)([String](../../system/string/)) override | 노드와 모든 자식의 연결된 값을 설정합니다. |
| void [set_InnerXml](./set_innerxml/)([String](../../system/string/)) override | 이 노드의 자식만을 나타내는 마크업을 설정합니다. |
| void [set_IsEmpty](./set_isempty/)(**bool**) | 요소의 태그 형식을 설정합니다. |
| void [set_Prefix](./set_prefix/)([String](../../system/string/)) override | 이 노드의 네임스페이스 접두사를 설정합니다. |
| virtual void [set_Value](../xmlnode/set_value/)([String](../../system/string/)) | 노드의 값을 설정합니다. |
| virtual void [SetAttribute](./setattribute/)([String](../../system/string/), [String](../../system/string/)) | 지정된 이름을 가진 속성의 값을 설정합니다. |
| virtual [String](../../system/string/) [SetAttribute](./setattribute/)([String](../../system/string/), [String](../../system/string/), [String](../../system/string/)) | 지정된 로컬 이름과 네임스페이스 URI를 가진 속성의 값을 설정합니다. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlAttribute](../xmlattribute/)\> [SetAttributeNode](./setattributenode/)([SharedPtr](../../system/sharedptr/)\<[XmlAttribute](../xmlattribute/)\>) | 지정된 [XmlAttribute](../xmlattribute/)를 추가합니다. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlAttribute](../xmlattribute/)\> [SetAttributeNode](./setattributenode/)([String](../../system/string/), [String](../../system/string/)) | 지정된 [XmlAttribute](../xmlattribute/)를 추가합니다. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n번째 템플릿 인수를 공유 포인터 대신 약한 포인터로 설정합니다. 컨테이너의 포인터를 약한 모드로 전환할 수 있게 합니다. |
| int [SharedCount](../../system/object/sharedcount/)() const | 공유 참조 카운터의 현재 값을 가져옵니다. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 공유 참조 카운트를 증가시킵니다. 직접 호출해서는 안 되며, 대신 스마트 포인터나 ThisProtector를 사용하십시오. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 공유 참조 카운트를 감소시키고 반환합니다. 직접 호출해서는 안 되며, 대신 스마트 포인터나 ThisProtector를 사용하십시오. |
| virtual **bool** [Supports](../xmlnode/supports/)([String](../../system/string/), [String](../../system/string/)) | DOM 구현이 특정 기능을 구현했는지 테스트합니다. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) 메서드의 유사체입니다. 사용자 정의 객체를 문자열로 변환할 수 있게 합니다. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) 구문을 구현합니다. |
| void [Unlock](../../system/object/unlock/)() | C# lock() 구문의 잠금 해제를 구현합니다. 직접 호출하거나 [LockContext](../../system/lockcontext/) 감시 객체를 사용합니다. |
| virtual [virtualized_iterator](../../system.collections.generic/ienumerable/virtualized_iterator/) * [virtualizeBeginConstIterator](../../system.collections.generic/ienumerable/virtualizebeginconstiterator/)() const | 현재 컨테이너의 begin const 이터레이터 구현을 가져옵니다. |
| virtual [virtualized_iterator](../../system.collections.generic/ienumerable/virtualized_iterator/) * [virtualizeBeginIterator](../../system.collections.generic/ienumerable/virtualizebeginiterator/)() | 현재 컨테이너의 begin 이터레이터 구현을 가져옵니다. |
| virtual [virtualized_iterator](../../system.collections.generic/ienumerable/virtualized_iterator/) * [virtualizeEndConstIterator](../../system.collections.generic/ienumerable/virtualizeendconstiterator/)() const | 현재 컨테이너의 end const 이터레이터 구현을 가져옵니다. |
| virtual [virtualized_iterator](../../system.collections.generic/ienumerable/virtualized_iterator/) * [virtualizeEndIterator](../../system.collections.generic/ienumerable/virtualizeenditerator/)() | 현재 컨테이너의 end 이터레이터 구현을 가져옵니다. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 약한 참조 카운트를 증가시킵니다. 직접 호출해서는 안 되며, 대신 스마트 포인터나 ThisProtector를 사용하십시오. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 약한 참조 카운트를 감소시킵니다. 직접 호출해서는 안 되며, 대신 스마트 포인터나 ThisProtector를 사용하십시오. |
| void [WriteContentTo](./writecontentto/)(const [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../xmlwriter/)\>\&) override | 노드의 모든 자식을 지정된 [XmlWriter](../xmlwriter/)에 저장합니다. |
| void [WriteTo](./writeto/)(const [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../xmlwriter/)\>\&) override | 현재 노드를 지정된 [XmlWriter](../xmlwriter/)에 저장합니다. |
| virtual  [~Object](../../system/object/~object/)() | 객체를 파괴합니다. 모든 내부 데이터 구조를 해제합니다. |
## Typedefs

| Typedef | Description |
| --- | --- |
| [Ptr](./ptr/) | 이 클래스의 인스턴스에 대한 공유 포인터 별칭입니다. |
## Remarks

이 클래스의 객체는 [System::MakeObject()](../../system/makeobject/) 함수를 사용하여 할당해야 합니다. 스택에 해당 유형의 인스턴스를 만들거나 operator new를 사용하지 마십시오. 이렇게 하면 런타임 오류 및/또는 어설션 오류가 발생합니다. 항상 이 클래스를 [System::SmartPtr](../../system/smartptr/) 포인터로 감싸고, 이 포인터를 함수 인자로 전달하십시오. 

## See Also

* 클래스 [XmlLinkedNode](../xmllinkednode/)
* 네임스페이스 [System::Xml](../)
* 라이브러리 [Aspose.Slides](../../)