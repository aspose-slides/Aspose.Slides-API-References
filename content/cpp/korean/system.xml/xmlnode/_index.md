---
title: XmlNode
second_title: Aspose.Slides for C++ API 레퍼런스
description: XML 문서에서 단일 노드를 나타냅니다.
type: docs
weight: 326
url: /ko/system.xml/xmlnode/
---
## XmlNode 클래스


XML 문서에서 단일 노드를 나타냅니다.

```cpp
class XmlNode : public System::Collections::Generic::IEnumerable<SharedPtr<System::Xml::XmlNode>>,
                public System::Xml::XPath::IXPathNavigable
```

## 메서드

| 메서드 | 설명 |
| --- | --- |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlNode](./)\> [AppendChild](./appendchild/)([SharedPtr](../../system/sharedptr/)\<[XmlNode](./)\>) | 지정된 노드를 이 노드의 자식 노드 리스트 끝에 추가합니다. |
| [iterator](../../system.collections.generic/ienumerable/iterator/) [begin](../../system.collections.generic/ienumerable/begin/)() | 컬렉션의 첫 번째 요소(있는 경우)를 가리키는 반복자를 가져옵니다. [GetEnumerator()](../../system.collections.generic/ienumerable/getenumerator/)가 T의 복사 객체를 반환하기 때문에 이 반복자를 사용해 참조된 객체를 변경할 수 없습니다. |
| [const_iterator](../../system.collections.generic/ienumerable/const_iterator/) [begin](../../system.collections.generic/ienumerable/begin/)() const | 컬렉션의 const 한정 인스턴스에서 첫 번째 요소(있는 경우)를 가리키는 반복자를 가져옵니다. |
| [const_iterator](../../system.collections.generic/ienumerable/const_iterator/) [cbegin](../../system.collections.generic/ienumerable/cbegin/)() const | 컬렉션에서 첫 번째 const 한정 요소(있는 경우)를 가리키는 반복자를 가져옵니다. |
| [const_iterator](../../system.collections.generic/ienumerable/const_iterator/) [cend](../../system.collections.generic/ienumerable/cend/)() const | 컬렉션에서 마지막 const 한정 요소 바로 다음을 가리키는 반복자를 가져옵니다. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlNode](./)\> [Clone](./clone/)() | 이 노드의 복제본을 생성합니다. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlNode](./)\> [CloneNode](./clonenode/)(**bool**) | 파생 클래스에서 재정의될 때 노드의 복제본을 생성합니다. |
| [SharedPtr](../../system/sharedptr/)\<[XPath::XPathNavigator](../../system.xml.xpath/xpathnavigator/)\> [CreateNavigator](./createnavigator/)() override | 이 객체를 탐색하기 위한 XPathNavigator를 생성합니다. |
| [iterator](../../system.collections.generic/ienumerable/iterator/) [end](../../system.collections.generic/ienumerable/end/)() | 컬렉션에서 마지막 요소 바로 다음을 가리키는 반복자를 가져옵니다. [GetEnumerator()](../../system.collections.generic/ienumerable/getenumerator/)가 T의 복사 객체를 반환하기 때문에 이 반복자를 사용해 참조된 객체를 변경할 수 없습니다. |
| [const_iterator](../../system.collections.generic/ienumerable/const_iterator/) [end](../../system.collections.generic/ienumerable/end/)() const | 컬렉션의 const 한정 인스턴스에서 마지막 요소 바로 다음을 가리키는 반복자를 가져옵니다. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) 의미를 사용해 객체를 비교합니다. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# 스타일로 레퍼런스 타입 객체를 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# 스타일로 값 타입 객체를 비교합니다. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | IEC 60559:1989에 따르면 NaN은 어떤 값과도 같지 않지만, C# 스타일 부동소수점 비교를 흉내 내어 두 NaN을 동일하게 간주합니다. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | IEC 60559:1989에 따르면 NaN은 어떤 값과도 같지 않지만, C# 스타일 부동소수점 비교를 흉내 내어 두 NaN을 동일하게 간주합니다. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 내부 용도 전용입니다. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlAttributeCollection](../xmlattributecollection/)\> [get_Attributes](./get_attributes/)() | 이 노드의 속성을 포함하는 [XmlAttributeCollection](../xmlattributecollection/)를 반환합니다. |
| virtual [String](../../system/string/) [get_BaseURI](./get_baseuri/)() | 현재 노드의 기본 URI를 반환합니다. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlNodeList](../xmlnodelist/)\> [get_ChildNodes](./get_childnodes/)() | 노드의 모든 자식 노드를 반환합니다. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlNode](./)\> [get_FirstChild](./get_firstchild/)() | 노드의 첫 번째 자식을 반환합니다. |
| virtual **bool** [get_HasChildNodes](./get_haschildnodes/)() | 이 노드가 자식 노드를 가지고 있는지 여부를 나타내는 값을 반환합니다. |
| virtual [String](../../system/string/) [get_InnerText](./get_innertext/)() | 노드와 모든 자식 노드의 값을 연결한 문자열을 반환합니다. |
| virtual [String](../../system/string/) [get_InnerXml](./get_innerxml/)() | 이 노드의 자식 노드만을 나타내는 마크업을 반환합니다. |
| virtual **bool** [get_IsReadOnly](./get_isreadonly/)() | 노드가 읽기 전용인지 여부를 나타내는 값을 반환합니다. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlNode](./)\> [get_LastChild](./get_lastchild/)() | 노드의 마지막 자식을 반환합니다. |
| virtual [String](../../system/string/) [get_LocalName](./get_localname/)() | 파생 클래스에서 재정의될 때 노드의 로컬 이름을 반환합니다. |
| virtual [String](../../system/string/) [get_Name](./get_name/)() | 파생 클래스에서 재정의될 때 노드의 정규화된 이름을 반환합니다. |
| virtual [String](../../system/string/) [get_NamespaceURI](./get_namespaceuri/)() | 이 노드의 네임스페이스 URI를 반환합니다. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlNode](./)\> [get_NextSibling](./get_nextsibling/)() | 이 노드 바로 뒤에 오는 노드를 반환합니다. |
| virtual [XmlNodeType](../xmlnodetype/) [get_NodeType](./get_nodetype/)() | 파생 클래스에서 재정의될 때 현재 노드의 유형을 반환합니다. |
| virtual [String](../../system/string/) [get_OuterXml](./get_outerxml/)() | 이 노드와 모든 자식 노드를 포함하는 마크업을 반환합니다. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlDocument](../xmldocument/)\> [get_OwnerDocument](./get_ownerdocument/)() | 이 노드가 속한 [XmlDocument](../xmldocument/)를 반환합니다. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlNode](./)\> [get_ParentNode](./get_parentnode/)() | 이 노드의 부모를 반환합니다(부모를 가질 수 있는 노드에 대해). |
| virtual [String](../../system/string/) [get_Prefix](./get_prefix/)() | 이 노드의 네임스페이스 접두사를 반환합니다. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlNode](./)\> [get_PreviousSibling](./get_previoussibling/)() | 이 노드 바로 앞에 있는 노드를 반환합니다. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlNode](./)\> [get_PreviousText](./get_previoustext/)() | 이 노드 바로 앞에 있는 텍스트 노드를 반환합니다. |
| virtual [SharedPtr](../../system/sharedptr/)\<[Schema::IXmlSchemaInfo](../../system.xml.schema/ixmlschemainfo/)\> [get_SchemaInfo](./get_schemainfo/)() | 스키마 검증 결과로 이 노드에 할당된 스키마 검증 후 정보 집합을 반환합니다. |
| virtual [String](../../system/string/) [get_Value](./get_value/)() | 노드의 값을 반환합니다. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | 객체와 연관된 참조 카운터 데이터 구조를 가져옵니다. |
| [SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IEnumerator](../../system.collections.generic/ienumerator/)\<[SharedPtr](../../system/sharedptr/)\<[XmlNode](./)\>\>\> [GetEnumerator](./getenumerator/)() override | 현재 노드의 자식 노드를 순회하는 열거자를 반환합니다. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) 메서드의 유사체. 사용자 정의 객체의 해싱을 지원합니다. |
| virtual [String](../../system/string/) [GetNamespaceOfPrefix](./getnamespaceofprefix/)([String](../../system/string/)) | 현재 노드 범위 내에서 주어진 접두사에 가장 가까운 **xmlns** 선언을 찾아 해당 선언의 네임스페이스 URI를 반환합니다. |
| virtual [String](../../system/string/) [GetPrefixOfNamespace](./getprefixofnamespace/)([String](../../system/string/)) | 현재 노드 범위 내에서 주어진 네임스페이스 URI에 가장 가까운 **xmlns** 선언을 찾아 해당 선언에 정의된 접두사를 반환합니다. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | 객체의 실제 형식을 가져옵니다. C# [System.Object.GetType()](../../system/object/gettype/) 호출의 유사체. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlElement](../xmlelement/)\> [idx_get](./idx_get/)([String](../../system/string/)) | 지정된 [XmlNode::get_Name](./get_name/)를 가진 첫 번째 자식 요소를 반환합니다. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlElement](../xmlelement/)\> [idx_get](./idx_get/)([String](../../system/string/), [String](../../system/string/)) | 지정된 [XmlNode::get_LocalName](./get_localname/)와 [XmlNode::get_NamespaceURI](./get_namespaceuri/) 값을 가진 첫 번째 자식 요소를 반환합니다. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlNode](./)\> [InsertAfter](./insertafter/)([SharedPtr](../../system/sharedptr/)\<[XmlNode](./)\>, [SharedPtr](../../system/sharedptr/)\<[XmlNode](./)\>) | 지정된 노드를 지정된 기준 노드 바로 뒤에 삽입합니다. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlNode](./)\> [InsertBefore](./insertbefore/)([SharedPtr](../../system/sharedptr/)\<[XmlNode](./)\>, [SharedPtr](../../system/sharedptr/)\<[XmlNode](./)\>) | 지정된 노드를 지정된 기준 노드 바로 앞에 삽입합니다. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | 객체가 targetType으로 설명된 유형의 인스턴스를 나타내는지 확인합니다. C# 'is' 연산자의 유사체. |
| T [LINQ_Aggregate](../../system.collections.generic/ienumerable/linq_aggregate/)(const [Func](../../system/func/)\<T, T, T\>\&) | 시퀀스에 누적 함수를 적용합니다. |
| **bool** [LINQ_All](../../system.collections.generic/ienumerable/linq_all/)(std::function\<**bool**(T)>) | 시퀀스의 모든 요소가 조건을 만족하는지 여부를 결정합니다. |
| **bool** [LINQ_Any](../../system.collections.generic/ienumerable/linq_any/)() | 시퀀스에 요소가 하나라도 있는지 여부를 결정합니다. |
| **bool** [LINQ_Any](../../system.collections.generic/ienumerable/linq_any/)(std::function\<**bool**(T)>) | 시퀀스에 요소가 존재하거나 조건을 만족하는지 여부를 결정합니다. |
| T [LINQ_Average](../../system.collections.generic/ienumerable/linq_average/)() | 숫자 값 시퀀스의 평균을 계산합니다. |
| ResultType [LINQ_Average](../../system.collections.generic/ienumerable/linq_average/)(const [Func](../../system/func/)\<T, ResultType\>\&) | 입력 시퀀스의 각 요소에 변환 함수를 적용해 얻은 값들의 평균을 계산합니다. |
| ResultType [LINQ_Average](../../system.collections.generic/ienumerable/linq_average/)(const [Func](../../system/func/)\<Source, ResultType\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_Cast](../../system.collections.generic/ienumerable/linq_cast/)() | 요소들을 지정된 유형으로 캐스팅합니다. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_Cast](../../system.collections.generic/ienumerable/linq_cast/)() |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Concat](../../system.collections.generic/ienumerable/linq_concat/)([SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\>) | 두 시퀀스를 연결합니다. |
| **bool** [LINQ_Contains](../../system.collections.generic/ienumerable/linq_contains/)(T) | 시퀀스에 지정된 값이 포함되어 있는지 확인합니다. |
| int [LINQ_Count](../../system.collections.generic/ienumerable/linq_count/)() | 시퀀스의 요소 개수를 반환합니다(직접 카운팅으로 계산). |
| int [LINQ_Count](../../system.collections.generic/ienumerable/linq_count/)(const [Func](../../system/func/)\<T, **bool**\>\&) | 주어진 조건을 만족하는 시퀀스 요소의 개수를 반환합니다. |
| T [LINQ_ElementAt](../../system.collections.generic/ienumerable/linq_elementat/)(int) | 시퀀스에서 지정된 인덱스에 해당하는 요소를 반환합니다. |
| T [LINQ_ElementAtOrDefault](../../system.collections.generic/ienumerable/linq_elementatordefault/)(int) | 시퀀스에서 지정된 인덱스에 해당하는 요소를 반환합니다. |
| T [LINQ_First](../../system.collections.generic/ienumerable/linq_first/)() | 시퀀스의 첫 번째 요소를 반환합니다. |
| T [LINQ_First](../../system.collections.generic/ienumerable/linq_first/)(const [Func](../../system/func/)\<T, **bool**\>\&) | 지정된 조건을 만족하는 시퀀스의 첫 번째 요소를 반환합니다. |
| T [LINQ_FirstOrDefault](../../system.collections.generic/ienumerable/linq_firstordefault/)() | 시퀀스의 첫 번째 요소를 반환하며, 시퀀스가 비어 있으면 기본값을 반환합니다. |
| T [LINQ_FirstOrDefault](../../system.collections.generic/ienumerable/linq_firstordefault/)(std::function\<**bool**(T)>) | 조건을 만족하는 시퀀스의 첫 번째 요소를 반환하고, 해당 요소가 없으면 기본값을 반환합니다. |
| [System::SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[System::SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, T\>\>\>\> [LINQ_GroupBy](../../system.collections.generic/ienumerable/linq_groupby/)([System::Func](../../system/func/)\<T, Key\>) | 시퀀스의 요소들을 그룹화합니다. |
| [System::SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[System::SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Element\>\>\>\> [LINQ_GroupBy](../../system.collections.generic/ienumerable/linq_groupby/)([System::Func](../../system/func/)\<T, Key\>, [System::Func](../../system/func/)\<T, Element\>) | 시퀀스의 요소들을 그룹화합니다. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Source\>\>\>\> [LINQ_GroupBy](../../system.collections.generic/ienumerable/linq_groupby/)([System::Func](../../system/func/)\<Source, Key\>) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Element\>\>\>\> [LINQ_GroupBy](../../system.collections.generic/ienumerable/linq_groupby/)([System::Func](../../system/func/)\<Source, Key\>, [System::Func](../../system/func/)\<Source, Element\>) |  |
| T [LINQ_Last](../../system.collections.generic/ienumerable/linq_last/)() | 시퀀스의 마지막 요소를 반환합니다. |
| T [LINQ_LastOrDefault](../../system.collections.generic/ienumerable/linq_lastordefault/)() | 시퀀스의 마지막 요소를 반환하며, 시퀀스가 비어 있으면 기본값을 반환합니다. |
| ResultType [LINQ_Max](../../system.collections.generic/ienumerable/linq_max/)(const [Func](../../system/func/)\<T, ResultType\>\&) | 일반 시퀀스의 각 요소에 변환 함수를 적용하고, 그 결과 중 최대값을 반환합니다. |
| ResultType [LINQ_Max](../../system.collections.generic/ienumerable/linq_max/)(const [Func](../../system/func/)\<Source, ResultType\>\&) |  |
| ResultType [LINQ_Min](../../system.collections.generic/ienumerable/linq_min/)(const [Func](../../system/func/)\<T, ResultType\>\&) | 일반 시퀀스의 각 요소에 변환 함수를 적용하고, 그 결과 중 최소값을 반환합니다. |
| ResultType [LINQ_Min](../../system.collections.generic/ienumerable/linq_min/)(const [Func](../../system/func/)\<Source, ResultType\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_OfType](../../system.collections.generic/ienumerable/linq_oftype/)() | 지정된 유형을 기준으로 시퀀스 요소를 필터링합니다. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_OfType](../../system.collections.generic/ienumerable/linq_oftype/)() |  |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<T\>\> [LINQ_OrderBy](../../system.collections.generic/ienumerable/linq_orderby/)(const [Func](../../system/func/)\<T, Key\>\&) | keySelector가 선택한 키 값에 따라 시퀀스 요소를 오름차순으로 정렬합니다. |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<Source\>\> [LINQ_OrderBy](../../system.collections.generic/ienumerable/linq_orderby/)(const [Func](../../system/func/)\<Source, Key\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<T\>\> [LINQ_OrderByDescending](../../system.collections.generic/ienumerable/linq_orderbydescending/)(const [Func](../../system/func/)\<T, Key\>\&) | keySelector가 선택한 키 값에 따라 시퀀스 요소를 내림차순으로 정렬합니다. |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<Source\>\> [LINQ_OrderByDescending](../../system.collections.generic/ienumerable/linq_orderbydescending/)(const [Func](../../system/func/)\<Source, Key\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Reverse](../../system.collections.generic/ienumerable/linq_reverse/)() | 시퀀스 요소의 순서를 반전시킵니다. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_Select](../../system.collections.generic/ienumerable/linq_select/)(const [Func](../../system/func/)\<T, ResultType\>\&) | 시퀀스 요소를 변환합니다. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_Select](../../system.collections.generic/ienumerable/linq_select/)(const [Func](../../system/func/)\<T, **int32_t**, ResultType\>\&) | 요소의 인덱스를 포함하여 시퀀스의 각 요소를 새로운 형태로 변환합니다. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_Select](../../system.collections.generic/ienumerable/linq_select/)(const [Func](../../system/func/)\<Source, Result\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_Select](../../system.collections.generic/ienumerable/linq_select/)(const [Func](../../system/func/)\<Source, **int32_t**, Result\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_SelectMany](../../system.collections.generic/ienumerable/linq_selectmany/)(const [Func](../../system/func/)\<T, [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\>\>\&) | 시퀀스의 각 요소를 투영하고, 결과 시퀀스를 하나의 시퀀스로 결합합니다. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_SelectMany](../../system.collections.generic/ienumerable/linq_selectmany/)(const [Func](../../system/func/)\<Source, [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\>\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Skip](../../system.collections.generic/ienumerable/linq_skip/)(**int32_t**) | 시퀀스 시작에서 지정된 수만큼 연속된 요소를 건너뛰고 나머지를 반환합니다. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Take](../../system.collections.generic/ienumerable/linq_take/)(**int32_t**) | 시퀀스 시작에서 지정된 수만큼 연속된 요소를 반환합니다. |
| [System::ArrayPtr](../../system/arrayptr/)\<T\> [LINQ_ToArray](../../system.collections.generic/ienumerable/linq_toarray/)() | 시퀀스로부터 배열을 생성합니다. |
| [SharedPtr](../../system/sharedptr/)\<[List](../../system.collections.generic/list/)\<T\>\> [LINQ_ToList](../../system.collections.generic/ienumerable/linq_tolist/)() | 시퀀스로부터 List<T>를 생성합니다. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Where](../../system.collections.generic/ienumerable/linq_where/)(std::function\<**bool**(T)>) | 지정된 프레디케이트를 기준으로 시퀀스를 필터링합니다. |
| void [Lock](../../system/object/lock/)() | C# lock() 문을 구현한 잠금 기능입니다. 직접 호출하거나 [LockContext](../../system/lockcontext/) 센트리 객체를 사용하십시오. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) 메서드의 유사체. 사용자 정의 타입 복제를 지원합니다. |
| virtual void [Normalize](./normalize/)() | 이 [XmlNode](./) 아래 전체 깊이의 서브 트리에서 모든 [XmlText](../xmltext/) 노드를 "정상" 형태로 변환합니다. 이 형태에서는 마크업(태그, 주석, 처리 명령, CDATA 섹션 및 엔터티 참조)만이 [XmlText](../xmltext/) 노드들을 구분하며, 인접한 [XmlText](../xmltext/) 노드가 존재하지 않습니다. |
|  [Object](../../system/object/object/)() | 객체를 생성합니다. 모든 내부 데이터 구조를 초기화합니다. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | 복사 생성자입니다. 실제로는 아무 것도 복사하지 않으며, 새 객체를 초기화하고 서브클래스 복사 구성을 가능하게 합니다. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 대입 연산자입니다. 실제로는 아무 것도 복사하지 않으며, 새 객체를 초기화하고 서브클래스 복사 구성을 가능하게 합니다. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlNode](./)\> [PrependChild](./prependchild/)([SharedPtr](../../system/sharedptr/)\<[XmlNode](./)\>) | 지정된 노드를 이 노드의 자식 노드 리스트 앞에 추가합니다. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 객체를 레퍼런스로 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 객체를 레퍼런스로 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 값 타입 객체와 nullptr를 레퍼런스로 비교합니다. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/)의 문자열과 nullptr 경우에 대한 특수화입니다. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/)의 문자열 경우에 대한 특수화입니다. |
| virtual void [RemoveAll](./removeall/)() | 현재 노드의 모든 자식 노드 및/또는 속성을 제거합니다. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlNode](./)\> [RemoveChild](./removechild/)([SharedPtr](../../system/sharedptr/)\<[XmlNode](./)\>) | 지정된 자식 노드를 제거합니다. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 지정된 값만큼 공유 참조 카운트를 감소시킵니다. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlNode](./)\> [ReplaceChild](./replacechild/)([SharedPtr](../../system/sharedptr/)\<[XmlNode](./)\>, [SharedPtr](../../system/sharedptr/)\<[XmlNode](./)\>) | 자식 노드 **oldChild**를 **newChild** 노드로 교체합니다. |
| [SharedPtr](../../system/sharedptr/)\<[XmlNodeList](../xmlnodelist/)\> [SelectNodes](./selectnodes/)(const [String](../../system/string/)\&) | [XPath](../../system.xml.xpath/) 식과 일치하는 노드 리스트를 선택합니다. |
| [SharedPtr](../../system/sharedptr/)\<[XmlNodeList](../xmlnodelist/)\> [SelectNodes](./selectnodes/)(const [String](../../system/string/)\&, const [SharedPtr](../../system/sharedptr/)\<[XmlNamespaceManager](../xmlnamespacemanager/)\>\&) | [XPath](../../system.xml.xpath/) 식과 일치하는 노드 리스트를 선택합니다. [XPath](../../system.xml.xpath/) 식에서 발견된 모든 접두사는 제공된 [XmlNamespaceManager](../xmlnamespacemanager/)를 사용해 해석됩니다. |
| [SharedPtr](../../system/sharedptr/)\<[XmlNode](./)\> [SelectSingleNode](./selectsinglenode/)(const [String](../../system/string/)\&) | [XPath](../../system.xml.xpath/) 식과 일치하는 첫 번째 [XmlNode](./)를 선택합니다. |
| [SharedPtr](../../system/sharedptr/)\<[XmlNode](./)\> [SelectSingleNode](./selectsinglenode/)(const [String](../../system/string/)\&, const [SharedPtr](../../system/sharedptr/)\<[XmlNamespaceManager](../xmlnamespacemanager/)\>\&) | [XPath](../../system.xml.xpath/) 식과 일치하는 첫 번째 [XmlNode](./)를 선택합니다. [XPath](../../system.xml.xpath/) 식에서 발견된 모든 접두사는 제공된 [XmlNamespaceManager](../xmlnamespacemanager/)를 사용해 해석됩니다. |
| virtual void [set_InnerText](./set_innertext/)([String](../../system/string/)) | 노드와 모든 자식 노드의 값을 연결하여 설정합니다. |
| virtual void [set_InnerXml](./set_innerxml/)([String](../../system/string/)) | 이 노드의 자식 노드만을 나타내는 마크업을 설정합니다. |
| virtual void [set_Prefix](./set_prefix/)([String](../../system/string/)) | 이 노드의 네임스페이스 접두사를 설정합니다. |
| virtual void [set_Value](./set_value/)([String](../../system/string/)) | 노드의 값을 설정합니다. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n번째 템플릿 인자를 강한 포인터가 아닌 약한 포인터로 설정합니다. 컨테이너 내 포인터를 약한 모드로 전환할 수 있습니다. |
| int [SharedCount](../../system/object/sharedcount/)() const | 현재 공유 참조 카운터 값을 가져옵니다. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 공유 참조 카운트를 증가시킵니다. 직접 호출해서는 안 되며, 대신 스마트 포인터 또는 ThisProtector를 사용하십시오. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 공유 참조 카운트를 감소시키고 반환합니다. 직접 호출해서는 안 되며, 대신 스마트 포인터 또는 ThisProtector를 사용하십시오. |
| virtual **bool** [Supports](./supports/)([String](../../system/string/), [String](../../system/string/)) | DOM 구현이 특정 기능을 지원하는지 테스트합니다. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) 메서드의 유사체. 사용자 정의 객체를 문자열로 변환할 수 있게 합니다. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) 구문을 구현합니다. |
| void [Unlock](../../system/object/unlock/)() | C# lock() 문에 대한 잠금 해제를 구현합니다. 직접 호출하거나 [LockContext](../../system/lockcontext/) 센트리 객체를 사용하십시오. |
| virtual [virtualized_iterator](../../system.collections.generic/ienumerable/virtualized_iterator/) * [virtualizeBeginConstIterator](../../system.collections.generic/ienumerable/virtualizebeginconstiterator/)() const | 현재 컨테이너에 대한 const begin 반복자 구현을 가져옵니다. |
| virtual [virtualized_iterator](../../system.collections.generic/ienumerable/virtualized_iterator/) * [virtualizeBeginIterator](../../system.collections.generic/ienumerable/virtualizebeginiterator/)() | 현재 컨테이너에 대한 begin 반복자 구현을 가져옵니다. |
| virtual [virtualized_iterator](../../system.collections.generic/ienumerable/virtualized_iterator/) * [virtualizeEndConstIterator](../../system.collections.generic/ienumerable/virtualizeendconstiterator/)() const | 현재 컨테이너에 대한 const end 반복자 구현을 가져옵니다. |
| virtual [virtualized_iterator](../../system.collections.generic/ienumerable/virtualized_iterator/) * [virtualizeEndIterator](../../system.collections.generic/ienumerable/virtualizeenditerator/)() | 현재 컨테이너에 대한 end 반복자 구현을 가져옵니다. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 약한 참조 카운트를 증가시킵니다. 직접 호출해서는 안 되며, 대신 스마트 포인터 또는 ThisProtector를 사용하십시오. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 약한 참조 카운트를 감소시킵니다. 직접 호출해서는 안 되며, 대신 스마트 포인터 또는 ThisProtector를 사용하십시오. |
| virtual void [WriteContentTo](./writecontentto/)(const [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../xmlwriter/)\>\&) | 파생 클래스에서 재정의될 때 노드의 모든 자식 노드를 지정된 [XmlWriter](../xmlwriter/)에 저장합니다. |
| virtual void [WriteTo](./writeto/)(const [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../xmlwriter/)\>\&) | 파생 클래스에서 재정의될 때 현재 노드를 지정된 [XmlWriter](../xmlwriter/)에 저장합니다. |
| virtual  [~Object](../../system/object/~object/)() | 객체를 파괴합니다. 모든 내부 데이터 구조를 해제합니다.

## 타입정의

| 타입정의 | 설명 |
| --- | --- |
| [Ptr](./ptr/) | 이 클래스의 인스턴스에 대한 공유 포인터 별칭입니다.

## 또 보기

* 클래스 [IEnumerable](../../system.collections.generic/ienumerable/)
* 클래스 [IXPathNavigable](../../system.xml.xpath/ixpathnavigable/)
* 네임스페이스 [System::Xml](../)
* 라이브러리 [Aspose.Slides](../../)