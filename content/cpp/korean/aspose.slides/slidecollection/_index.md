---
title: SlideCollection
second_title: Aspose.Slides for C++ API 참조
description: 슬라이드 컬렉션을 나타냅니다.
type: docs
weight: 5188
url: /ko/aspose.slides/slidecollection/
---
## SlideCollection 클래스

Represents a collection of a slides.

```cpp
class SlideCollection : public Aspose::Slides::DomObject<System::SharedPtr<Aspose::Slides::Presentation>>,
                        public Aspose::Slides::ISlideCollection
```

## 메서드

| Method | Description |
| --- | --- |
| [System::SharedPtr](../../system/sharedptr/)\<[ISlide](../islide/)\> [AddClone](./addclone/)([System::SharedPtr](../../system/sharedptr/)\<[ISlide](../islide/)\>) override | 지정된 슬라이드의 복사본을 컬렉션의 끝에 추가합니다. |
| [System::SharedPtr](../../system/sharedptr/)\<[ISlide](../islide/)\> [AddClone](./addclone/)([System::SharedPtr](../../system/sharedptr/)\<[ISlide](../islide/)\>, [System::SharedPtr](../../system/sharedptr/)\<[ISection](../isection/)\>) override | 지정된 슬라이드의 복사본을 지정된 섹션의 끝에 추가합니다. |
| [System::SharedPtr](../../system/sharedptr/)\<[ISlide](../islide/)\> [AddClone](./addclone/)([System::SharedPtr](../../system/sharedptr/)\<[ISlide](../islide/)\>, [System::SharedPtr](../../system/sharedptr/)\<[ILayoutSlide](../ilayoutslide/)\>) override | 지정된 슬라이드의 복사본을 컬렉션의 끝에 추가합니다. |
| [System::SharedPtr](../../system/sharedptr/)\<[ISlide](../islide/)\> [AddClone](./addclone/)([System::SharedPtr](../../system/sharedptr/)\<[ISlide](../islide/)\>, [System::SharedPtr](../../system/sharedptr/)\<[IMasterSlide](../imasterslide/)\>, **bool**) override | 지정된 원본 슬라이드의 복사본을 컬렉션의 끝에 추가합니다. 적절한 레이아웃은 지정된 마스터에서 자동으로 선택됩니다(적절한 레이아웃은 원본 슬라이드 레이아웃과 Type 또는 Name이 같은 레이아웃). 적절한 레이아웃이 없으면 원본 슬라이드의 레이아웃이 복제됩니다(allowCloneMissingLayout가 true인 경우) 또는 PptxEditException이 발생합니다(allowCloneMissingLayout가 false인 경우). |
| [System::SharedPtr](../../system/sharedptr/)\<[ISlide](../islide/)\> [AddEmptySlide](./addemptyslide/)([System::SharedPtr](../../system/sharedptr/)\<[ILayoutSlide](../ilayoutslide/)\>) override | 새 빈 슬라이드를 컬렉션의 끝에 추가합니다. |
| [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[ISlide](../islide/)\>\> [AddFromHtml](./addfromhtml/)([System::String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[Import::IExternalResourceResolver](../../aspose.slides.import/iexternalresourceresolver/)\>, [System::String](../../system/string/)) override | HTML 텍스트에서 슬라이드를 생성하고 컬렉션의 끝에 추가합니다. |
| [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[ISlide](../islide/)\>\> [AddFromHtml](./addfromhtml/)([System::String](../../system/string/)) override | HTML 텍스트에서 슬라이드를 생성하고 컬렉션의 끝에 추가합니다. |
| [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[ISlide](../islide/)\>\> [AddFromHtml](./addfromhtml/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::TextReader](../../system.io/textreader/)\>, [System::SharedPtr](../../system/sharedptr/)\<[Import::IExternalResourceResolver](../../aspose.slides.import/iexternalresourceresolver/)\>, [System::String](../../system/string/)) override | HTML 텍스트에서 슬라이드를 생성하고 컬렉션의 끝에 추가합니다. |
| [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[ISlide](../islide/)\>\> [AddFromHtml](./addfromhtml/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::TextReader](../../system.io/textreader/)\>) override | HTML 텍스트에서 슬라이드를 생성하고 컬렉션의 끝에 추가합니다. |
| [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[ISlide](../islide/)\>\> [AddFromHtml](./addfromhtml/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>, [System::SharedPtr](../../system/sharedptr/)\<[Import::IExternalResourceResolver](../../aspose.slides.import/iexternalresourceresolver/)\>, [System::String](../../system/string/)) override | HTML 텍스트에서 슬라이드를 생성하고 컬렉션의 끝에 추가합니다. |
| [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[ISlide](../islide/)\>\> [AddFromHtml](./addfromhtml/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>) override | HTML 텍스트에서 슬라이드를 생성하고 컬렉션의 끝에 추가합니다. |
| [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[ISlide](../islide/)\>\> [AddFromPdf](./addfrompdf/)([System::String](../../system/string/)) override | PDF 문서에서 슬라이드를 생성하고 컬렉션의 끝에 추가합니다. |
| [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[ISlide](../islide/)\>\> [AddFromPdf](./addfrompdf/)([System::String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[Import::PdfImportOptions](../../aspose.slides.import/pdfimportoptions/)\>) override | PDF 문서에서 슬라이드를 생성하고 PDF 가져오기 옵션을 고려하여 컬렉션의 끝에 추가합니다. |
| [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[ISlide](../islide/)\>\> [AddFromPdf](./addfrompdf/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>) override | PDF 문서에서 슬라이드를 생성하고 컬렉션의 끝에 추가합니다. |
| [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[ISlide](../islide/)\>\> [AddFromPdf](./addfrompdf/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>, [System::SharedPtr](../../system/sharedptr/)\<[Import::PdfImportOptions](../../aspose.slides.import/pdfimportoptions/)\>) override | PDF 문서에서 슬라이드를 생성하고 컬렉션의 끝에 추가합니다. |
| [iterator](./iterator/) [begin](./begin/)() | 컬렉션의 첫 번째 요소를 가리키는 반복자를 반환합니다(있는 경우). |
| [const_iterator](./const_iterator/) [begin](./begin/)() const | 컬렉션의 const 제한 인스턴스에서 첫 번째 요소를 가리키는 반복자를 반환합니다(있는 경우). |
| [const_iterator](./const_iterator/) [cbegin](./cbegin/)() const | 컬렉션의 첫 번째 const 제한 요소를 가리키는 반복자를 반환합니다(있는 경우). |
| [const_iterator](./const_iterator/) [cend](./cend/)() const | 컬렉션의 마지막 const 제한 요소 바로 뒤를 가리키는 반복자를 반환합니다(있는 경우). |
| void [CopyTo](./copyto/)([System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[ISlide](../islide/)\>\>, **int32_t**) override | 컬렉션의 모든 요소를 지정된 배열에 복사합니다. |
| virtual void [CopyTo](../igenericcollection/copyto/)([System::ArrayPtr](../../system/arrayptr/)\<T\>, **int32_t**) | 컬렉션의 모든 요소를 지정된 배열에 복사합니다. |
| [iterator](./iterator/) [end](./end/)() | 컬렉션의 마지막 요소 바로 뒤를 가리키는 반복자를 반환합니다(있는 경우). |
| [const_iterator](./const_iterator/) [end](./end/)() const | 컬렉션의 const 제한 인스턴스에서 마지막 요소 바로 뒤를 가리키는 반복자를 반환합니다(있는 경우). |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) 구문을 사용하여 객체를 비교합니다. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# 스타일로 참조형 객체를 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# 스타일로 값형 객체를 비교합니다. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | IEC 60559:1989에 따르면 NaN은 어떤 값과도 같지 않지만, C# 스타일의 부동소수점 비교를 에뮬레이션하여 두 NaN을 동일하게 간주합니다. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | IEC 60559:1989에 따르면 NaN은 어떤 값과도 같지 않지만, C# 스타일의 부동소수점 비교를 에뮬레이션하여 두 NaN을 동일하게 간주합니다. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 내부용으로만 사용됩니다. |
| **int32_t** [get_Count](./get_count/)() override | 컬렉션에 실제 포함된 요소 수를 반환합니다. 읽기 전용 **int32_t**. |
| **bool** [get_IsSynchronized](./get_issynchronized/)() override | 컬렉션에 대한 접근이 동기화(스레드 안전)되는지 여부를 나타내는 값을 반환합니다. 읽기 전용 **bool**. |
| [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\> [get_SyncRoot](./get_syncroot/)() override | 동기화 루트를 반환합니다. 읽기 전용 [System::Object](../../system/object/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | 객체와 연결된 참조 카운터 데이터 구조를 반환합니다. |
| [System::SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::IEnumerator](../../system.collections.generic/ienumerator/)\<[System::SharedPtr](../../system/sharedptr/)\<[ISlide](../islide/)\>\>\> [GetEnumerator](./getenumerator/)() override | 컬렉션을 순회하는 열거자를 반환합니다. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) 메서드와 유사합니다. 사용자 정의 객체의 해시를 가능하게 합니다. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | C# [System.Object.GetType()](../../system/object/gettype/) 호출과 유사합니다. |
| [System::SharedPtr](../../system/sharedptr/)\<[ISlide](../islide/)\> [idx_get](./idx_get/)(**int32_t**) override | 지정된 인덱스에 있는 요소를 반환합니다. 읽기 전용 [Slide](../slide/). |
| **int32_t** [IndexOf](./indexof/)([System::SharedPtr](../../system/sharedptr/)\<[ISlide](../islide/)\>) override | 컬렉션에서 지정된 슬라이드의 인덱스를 반환합니다. |
| [System::SharedPtr](../../system/sharedptr/)\<[ISlide](../islide/)\> [InsertClone](./insertclone/)(**int32_t**, [System::SharedPtr](../../system/sharedptr/)\<[ISlide](../islide/)\>) override | 지정된 슬라이드의 복사본을 컬렉션의 지정된 위치에 삽입합니다. |
| [System::SharedPtr](../../system/sharedptr/)\<[ISlide](../islide/)\> [InsertClone](./insertclone/)(**int32_t**, [System::SharedPtr](../../system/sharedptr/)\<[ISlide](../islide/)\>, [System::SharedPtr](../../system/sharedptr/)\<[ILayoutSlide](../ilayoutslide/)\>) override | 지정된 슬라이드의 복사본을 컬렉션의 지정된 위치에 삽입합니다. |
| [System::SharedPtr](../../system/sharedptr/)\<[ISlide](../islide/)\> [InsertClone](./insertclone/)(**int32_t**, [System::SharedPtr](../../system/sharedptr/)\<[ISlide](../islide/)\>, [System::SharedPtr](../../system/sharedptr/)\<[IMasterSlide](../imasterslide/)\>, **bool**) override | 지정된 원본 슬라이드의 복사본을 컬렉션의 지정된 위치에 삽입합니다. 적절한 레이아웃은 지정된 마스터에서 자동으로 선택됩니다(적절한 레이아웃은 원본 슬라이드 레이아웃과 Type 또는 Name이 같은 레이아웃). 적절한 레이아웃이 없으면 원본 슬라이드의 레이아웃이 복제됩니다(allowCloneMissingLayout가 true인 경우) 또는 PptxEditException이 발생합니다(allowCloneMissingLayout가 false인 경우). |
| [System::SharedPtr](../../system/sharedptr/)\<[ISlide](../islide/)\> [InsertEmptySlide](./insertemptyslide/)(**int32_t**, [System::SharedPtr](../../system/sharedptr/)\<[ILayoutSlide](../ilayoutslide/)\>) override | 지정된 슬라이드의 복사본을 컬렉션의 지정된 위치에 삽입합니다. |
| [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[ISlide](../islide/)\>\> [InsertFromHtml](./insertfromhtml/)(**int32_t**, [System::String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[Import::IExternalResourceResolver](../../aspose.slides.import/iexternalresourceresolver/)\>, [System::String](../../system/string/)) override | HTML 텍스트에서 슬라이드를 생성하고 지정된 위치에 삽입합니다. |
| [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[ISlide](../islide/)\>\> [InsertFromHtml](./insertfromhtml/)(**int32_t**, [System::String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[Import::IExternalResourceResolver](../../aspose.slides.import/iexternalresourceresolver/)\>, [System::String](../../system/string/), **bool**) override | HTML 텍스트에서 슬라이드를 생성하고 지정된 위치에 삽입합니다. |
| [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[ISlide](../islide/)\>\> [InsertFromHtml](./insertfromhtml/)(**int32_t**, [System::String](../../system/string/)) override | HTML 텍스트에서 슬라이드를 생성하고 지정된 위치에 삽입합니다. |
| [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[ISlide](../islide/)\>\> [InsertFromHtml](./insertfromhtml/)(**int32_t**, [System::String](../../system/string/), **bool**) override | HTML 텍스트에서 슬라이드를 생성하고 지정된 위치에 삽입합니다. |
| [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[ISlide](../islide/)\>\> [InsertFromHtml](./insertfromhtml/)(**int32_t**, [System::SharedPtr](../../system/sharedptr/)\<[System::IO::TextReader](../../system.io/textreader/)\>, [System::SharedPtr](../../system/sharedptr/)\<[Import::IExternalResourceResolver](../../aspose.slides.import/iexternalresourceresolver/)\>, [System::String](../../system/string/)) override | HTML 텍스트에서 슬라이드를 생성하고 지정된 위치에 삽입합니다. |
| [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[ISlide](../islide/)\>\> [InsertFromHtml](./insertfromhtml/)(**int32_t**, [System::SharedPtr](../../system/sharedptr/)\<[System::IO::TextReader](../../system.io/textreader/)\>) override | HTML 텍스트에서 슬라이드를 생성하고 지정된 위치에 삽입합니다. |
| [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[ISlide](../islide/)\>\> [InsertFromHtml](./insertfromhtml/)(**int32_t**, [System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>, [System::SharedPtr](../../system/sharedptr/)\<[Import::IExternalResourceResolver](../../aspose.slides.import/iexternalresourceresolver/)\>, [System::String](../../system/string/)) override | HTML 텍스트에서 슬라이드를 생성하고 지정된 위치에 삽입합니다. |
| [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[ISlide](../islide/)\>\> [InsertFromHtml](./insertfromhtml/)(**int32_t**, [System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>, [System::SharedPtr](../../system/sharedptr/)\<[Import::IExternalResourceResolver](../../aspose.slides.import/iexternalresourceresolver/)\>, [System::String](../../system/string/), **bool**) override | HTML 텍스트에서 슬라이드를 생성하고 지정된 위치에 삽입합니다. |
| [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[ISlide](../islide/)\>\> [InsertFromHtml](./insertfromhtml/)(**int32_t**, [System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>) override | HTML 텍스트에서 슬라이드를 생성하고 지정된 위치에 삽입합니다. |
| [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[ISlide](../islide/)\>\> [InsertFromHtml](./insertfromhtml/)(**int32_t**, [System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>, **bool**) override | HTML 텍스트에서 슬라이드를 생성하고 지정된 위치에 삽입합니다. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | 객체가 targetType이 설명하는 유형의 인스턴스인지 확인합니다. C# 'is' 연산자와 유사합니다. |
| T [LINQ_Aggregate](../../system.collections.generic/ienumerable/linq_aggregate/)(const [Func](../../system/func/)\<T, T, T\>\&) | 시퀀스에 누적 함수 적용합니다. |
| **bool** [LINQ_All](../../system.collections.generic/ienumerable/linq_all/)(std::function\<**bool**(T)>) | 시퀀스의 모든 요소가 조건을 만족하는지 여부를 판단합니다. |
| **bool** [LINQ_Any](../../system.collections.generic/ienumerable/linq_any/)() | 시퀀스에 요소가 하나라도 있는지 판단합니다. |
| **bool** [LINQ_Any](../../system.collections.generic/ienumerable/linq_any/)(std::function\<**bool**(T)>) | 시퀀스에 요소가 존재하거나 조건을 만족하는지 판단합니다. |
| T [LINQ_Average](../../system.collections.generic/ienumerable/linq_average/)() | 숫자 값 시퀀스의 평균을 계산합니다. |
| ResultType [LINQ_Average](../../system.collections.generic/ienumerable/linq_average/)(const [Func](../../system/func/)\<T, ResultType\>\&) | 입력 시퀀스 각 요소에 변환 함수를 호출하여 얻은 값 시퀀스의 평균을 계산합니다. |
| ResultType [LINQ_Average](../../system.collections.generic/ienumerable/linq_average/)(const [Func](../../system/func/)\<Source, ResultType\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_Cast](../../system.collections.generic/ienumerable/linq_cast/)() | 요소들을 지정된 유형으로 캐스팅합니다. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_Cast](../../system.collections.generic/ienumerable/linq_cast/)() |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Concat](../../system.collections.generic/ienumerable/linq_concat/)([SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\>) | 두 시퀀스를 연결합니다. |
| **bool** [LINQ_Contains](../../system.collections.generic/ienumerable/linq_contains/)(T) | 시퀀스에 지정된 값이 포함되어 있는지 판단합니다. |
| int [LINQ_Count](../../system.collections.generic/ienumerable/linq_count/)() | 시퀀스의 요소 수를 반환합니다(직접 카운트 방식). |
| int [LINQ_Count](../../system.collections.generic/ienumerable/linq_count/)(const [Func](../../system/func/)\<T, **bool**\>\&) | 시퀀스에서 지정된 조건을 만족하는 요소 수를 반환합니다. |
| T [LINQ_ElementAt](../../system.collections.generic/ienumerable/linq_elementat/)(int) | 시퀀스에서 지정된 인덱스에 있는 요소를 반환합니다. |
| T [LINQ_ElementAtOrDefault](../../system.collections.generic/ienumerable/linq_elementatordefault/)(int) | 시퀀스에서 지정된 인덱스에 있는 요소를 반환합니다. |
| T [LINQ_First](../../system.collections.generic/ienumerable/linq_first/)() | 시퀀스의 첫 번째 요소를 반환합니다. |
| T [LINQ_First](../../system.collections.generic/ienumerable/linq_first/)(const [Func](../../system/func/)\<T, **bool**\>\&) | 지정된 조건을 만족하는 시퀀스의 첫 번째 요소를 반환합니다. |
| T [LINQ_FirstOrDefault](../../system.collections.generic/ienumerable/linq_firstordefault/)() | 시퀀스의 첫 번째 요소를 반환하거나, 시퀀스가 비어 있으면 기본값을 반환합니다. |
| T [LINQ_FirstOrDefault](../../system.collections.generic/ienumerable/linq_firstordefault/)(std::function\<**bool**(T)>) | 조건을 만족하는 시퀀스의 첫 번째 요소를 반환하거나, 해당 요소가 없으면 기본값을 반환합니다. |
| [System::SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[System::SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, T\>\>\>\> [LINQ_GroupBy](../../system.collections.generic/ienumerable/linq_groupby/)([System::Func](../../system/func/)\<T, Key\>) | 시퀀스의 요소들을 그룹화합니다. |
| [System::SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[System::SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Element\>\>\>\> [LINQ_GroupBy](../../system.collections.generic/ienumerable/linq_groupby/)([System::Func](../../system/func/)\<T, Key\>, [System::Func](../../system/func/)\<T, Element\>) | 시퀀스의 요소들을 그룹화합니다. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Source\>\>\>\> [LINQ_GroupBy](../../system.collections.generic/ienumerable/linq_groupby/)([System::Func](../../system/func/)\<Source, Key\>) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Element\>\>\>\> [LINQ_GroupBy](../../system.collections.generic/ienumerable/linq_groupby/)([System::Func](../../system/func/)\<Source, Key\>, [System::Func](../../system/func/)\<Source, Element\>) |  |
| T [LINQ_Last](../../system.collections.generic/ienumerable/linq_last/)() | 시퀀스의 마지막 요소를 반환합니다. |
| T [LINQ_LastOrDefault](../../system.collections.generic/ienumerable/linq_lastordefault/)() | 시퀀스의 마지막 요소를 반환하거나, 시퀀스가 비어 있으면 기본값을 반환합니다. |
| ResultType [LINQ_Max](../../system.collections.generic/ienumerable/linq_max/)(const [Func](../../system/func/)\<T, ResultType\>\&) | 일반 시퀀스의 각 요소에 변환 함수를 호출하고 최대 결과값을 반환합니다. |
| ResultType [LINQ_Max](../../system.collections.generic/ienumerable/linq_max/)(const [Func](../../system/func/)\<Source, ResultType\>\&) |  |
| ResultType [LINQ_Min](../../system.collections.generic/ienumerable/linq_min/)(const [Func](../../system/func/)\<T, ResultType\>\&) | 일반 시퀀스의 각 요소에 변환 함수를 호출하고 최소 결과값을 반환합니다. |
| ResultType [LINQ_Min](../../system.collections.generic/ienumerable/linq_min/)(const [Func](../../system/func/)\<Source, ResultType\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_OfType](../../system.collections.generic/ienumerable/linq_oftype/)() | 지정된 유형에 따라 시퀀스의 요소를 필터링합니다. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_OfType](../../system.collections.generic/ienumerable/linq_oftype/)() |  |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<T\>\> [LINQ_OrderBy](../../system.collections.generic/ienumerable/linq_orderby/)(const [Func](../../system/func/)\<T, Key\>\&) | keySelector가 선택한 키 값에 따라 시퀀스의 요소를 오름차순으로 정렬합니다. |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<Source\>\> [LINQ_OrderBy](../../system.collections.generic/ienumerable/linq_orderby/)(const [Func](../../system/func/)\<Source, Key\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<T\>\> [LINQ_OrderByDescending](../../system.collections.generic/ienumerable/linq_orderbydescending/)(const [Func](../../system/func/)\<T, Key\>\&) | keySelector가 선택한 키 값에 따라 시퀀스의 요소를 내림차순으로 정렬합니다. |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<Source\>\> [LINQ_OrderByDescending](../../system.collections.generic/ienumerable/linq_orderbydescending/)(const [Func](../../system/func/)\<Source, Key\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Reverse](../../system.collections.generic/ienumerable/linq_reverse/)() | 시퀀스의 요소 순서를 역전시킵니다. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_Select](../../system.collections.generic/ienumerable/linq_select/)(const [Func](../../system/func/)\<T, ResultType\>\&) | 시퀀스의 요소를 변환합니다. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_Select](../../system.collections.generic/ienumerable/linq_select/)(const [Func](../../system/func/)\<T, **int32_t**, ResultType\>\&) | 요소의 인덱스를 포함하여 시퀀스의 각 요소를 새로운 형태로 변환합니다. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_Select](../../system.collections.generic/ienumerable/linq_select/)(const [Func](../../system/func/)\<Source, Result\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_Select](../../system.collections.generic/ienumerable/linq_select/)(const [Func](../../system/func/)\<Source, **int32_t**, Result\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_SelectMany](../../system.collections.generic/ienumerable/linq_selectmany/)(const [Func](../../system/func/)\<T, [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\>\>\&) | 시퀀스의 각 요소를 투영하고 결과 시퀀스를 하나로 결합합니다. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_SelectMany](../../system.collections.generic/ienumerable/linq_selectmany/)(const [Func](../../system/func/)\<Source, [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\>\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Skip](../../system.collections.generic/ienumerable/linq_skip/)(**int32_t**) | 시퀀스 시작에서 지정된 개수만큼 연속된 요소를 건너뛰고 나머지를 반환합니다. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Take](../../system.collections.generic/ienumerable/linq_take/)(**int32_t**) | 시퀀스 시작에서 지정된 개수만큼 연속된 요소를 반환합니다. |
| [System::ArrayPtr](../../system/arrayptr/)\<T\> [LINQ_ToArray](../../system.collections.generic/ienumerable/linq_toarray/)() | 시퀀스에서 배열을 생성합니다. |
| [SharedPtr](../../system/sharedptr/)\<[List](../../system.collections.generic/list/)\<T\>\> [LINQ_ToList](../../system.collections.generic/ienumerable/linq_tolist/)() | 시퀀스에서 List<T>를 생성합니다. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Where](../../system.collections.generic/ienumerable/linq_where/)(std::function\<**bool**(T)>) | 지정된 프레디케이트에 따라 시퀀스를 필터링합니다. |
| void [Lock](../../system/object/lock/)() | C# lock() 문을 구현한 잠금입니다. 직접 호출하거나 [LockContext](../../system/lockcontext/) 감시 객체를 사용하세요. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) 메서드와 유사합니다. 사용자 정의 유형 복제를 가능하게 합니다. |
|  [Object](../../system/object/object/)() | 객체를 생성합니다. 모든 내부 데이터 구조를 초기화합니다. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | 복사 생성자. 실제로는 아무것도 복사하지 않으며, 새 객체를 초기화하고 서브클래스 복사 생성을 가능하게 합니다. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 대입 연산자. 실제로는 아무것도 복사하지 않으며, 새 객체를 초기화하고 서브클래스 복사 생성을 가능하게 합니다. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 객체를 레퍼런스로 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 객체를 레퍼런스로 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 값형 객체를 nullptr와 레퍼런스로 비교합니다. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/)의 문자열 및 nullptr 경우에 대한 특수화입니다. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/)의 문자열 경우에 대한 특수화입니다. |
| void [Remove](./remove/)([System::SharedPtr](../../system/sharedptr/)\<[ISlide](../islide/)\>) override | 컬렉션에서 특정 객체의 첫 번째 발생을 제거합니다. |
| void [RemoveAt](./removeat/)(**int32_t**) override | 컬렉션에서 지정된 인덱스에 있는 요소를 제거합니다. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 지정된 값만큼 공유 참조 카운트를 감소시킵니다. |
| void [Reorder](./reorder/)(**int32_t**, [System::SharedPtr](../../system/sharedptr/)\<[ISlide](../islide/)\>) override | 컬렉션에서 슬라이드를 지정된 위치로 이동합니다. |
| void [Reorder](./reorder/)(**int32_t**, const [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[ISlide](../islide/)\>\>\&) override | 컬렉션에서 슬라이드를 지정된 위치로 이동합니다. [Slides](../)는 리스트에 나타나는 순서대로 인덱스부터 배치됩니다. |
| void [SetTemplateWeakPtr](./settemplateweakptr/)(**uint32_t**) override | n번째 템플릿 인수를 약한 포인터(공유 대신)로 설정합니다. 컨테이너의 포인터를 약한 모드로 전환할 수 있습니다. |
| int [SharedCount](../../system/object/sharedcount/)() const | 공유 참조 카운터의 현재 값을 반환합니다. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 공유 참조 카운트를 증가시킵니다. 직접 호출하면 안 되며, 스마트 포인터 또는 ThisProtector를 사용하세요. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 공유 참조 카운트를 감소시키고 반환합니다. 직접 호출하면 안 되며, 스마트 포인터 또는 ThisProtector를 사용하세요. |
| [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[ISlide](../islide/)\>\> [ToArray](./toarray/)() override | 모든 슬라이드를 포함한 배열을 생성하고 반환합니다. |
| [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[ISlide](../islide/)\>\> [ToArray](./toarray/)(**int32_t**, **int32_t**) override | 지정된 범위의 모든 슬라이드를 포함한 배열을 생성하고 반환합니다. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) 메서드와 유사합니다. 사용자 정의 객체를 문자열로 변환합니다. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) 구문을 구현합니다. |
| void [Unlock](../../system/object/unlock/)() | C# lock() 문의 잠금 해제를 구현합니다. 직접 호출하거나 [LockContext](../../system/lockcontext/) 감시 객체를 사용하세요. |
| [virtualized_iterator](./virtualized_iterator/) * [virtualizeBeginConstIterator](./virtualizebeginconstiterator/)() const override | 컬렉션의 const 제한 인스턴스에서 첫 번째 요소를 가리키는 반복자를 반환합니다(있는 경우). |
| [virtualized_iterator](./virtualized_iterator/) * [virtualizeBeginIterator](./virtualizebeginiterator/)() override | 컬렉션의 첫 번째 요소를 가리키는 반복자를 반환합니다(있는 경우). |
| [virtualized_iterator](./virtualized_iterator/) * [virtualizeEndConstIterator](./virtualizeendconstiterator/)() const override | 컬렉션의 const 제한 인스턴스에서 마지막 요소 바로 뒤를 가리키는 반복자를 반환합니다(있는 경우). |
| [virtualized_iterator](./virtualized_iterator/) * [virtualizeEndIterator](./virtualizeenditerator/)() override | 컬렉션의 마지막 요소 바로 뒤를 가리키는 반복자를 반환합니다(있는 경우). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 약한 참조 카운트를 증가시킵니다. 직접 호출하면 안 되며, 스마트 포인터 또는 ThisProtector를 사용하세요. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 약한 참조 카운트를 감소시킵니다. 직접 호출하면 안 되며, 스마트 포인터 또는 ThisProtector를 사용하세요. |
| virtual  [~Object](../../system/object/~object/)() | 객체를 파괴합니다. 모든 내부 데이터 구조를 해제합니다. |

## 타입 정의

| Typedef | Description |
| --- | --- |
| [iterator_holder_type](./iterator_holder_type/) | 현재 컬렉션에서 반복자 유형으로 사용되는 컬렉션 유형입니다. |
| [iterator](./iterator/) | 반복자 유형입니다. |
| [const_iterator](./const_iterator/) | const 반복자 유형입니다. |
| [virtualized_iterator_element](./virtualized_iterator_element/) | 가상화된 요소 유형입니다. |
| [virtualized_iterator](./virtualized_iterator/) | 가상화된 유형입니다. |

## 참고

* 클래스 [DomObject](../domobject/)
* 클래스 [ISlideCollection](../islidecollection/)
* 네임스페이스 [Aspose::Slides](../)
* 라이브러리 [Aspose.Slides](../../)