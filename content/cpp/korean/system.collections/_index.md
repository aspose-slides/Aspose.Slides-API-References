---
title: "System::Collections"
second_title: Aspose.Slides for C++ API 레퍼런스
description: 
type: docs
weight: 300
url: /ko/system.collections/
---
## 클래스

| 클래스 | 설명 |
| --- | --- |
| [BitArray](./bitarray/) | [Array](../system/array/) 비트이며 인덱스로 접근할 수 있습니다. 이 클래스의 객체는 [System::MakeObject()](../system/makeobject/) 함수만 사용하여 할당해야 합니다. 스택이나 operator new를 사용하여 이 유형의 인스턴스를 생성하면 런타임 오류 및/또는 어설션 오류가 발생합니다. 항상 이 클래스를 [System::SmartPtr](../system/smartptr/) 포인터로 감싸고 해당 포인터를 인수로 함수에 전달하십시오. |
| [BitArrayPtr](./bitarrayptr/) | [BitArray](./bitarray/)에 대한 포인터입니다. 이 유형은 다른 객체의 삭제를 관리하기 위한 포인터입니다. 스택에 할당하고 값이나 const 참조로 함수에 전달해야 합니다. |
| [CollectionBase](./collectionbase/) | 강력히 타입이 지정된 컬렉션을 위한 추상 기본 클래스를 제공합니다. |
| [ICollection](./icollection/) | 비제네릭 컬렉션 인터페이스를 정의합니다. |
| [IEnumerable](./ienumerable/) | [IEnumerable](./ienumerable/)은(는) 열거가 가능한 모든 비제네릭 컬렉션의 기본 인터페이스입니다. |
| [IEnumerator](./ienumerator/) | 몇몇 요소를 반복하는 데 사용할 수 있는 열거자의 인터페이스입니다. 이 클래스의 객체는 [System::MakeObject()](../system/makeobject/) 함수를 사용하여 할당해야 합니다. 스택이나 operator new를 사용하여 이 유형의 인스턴스를 생성하면 런타임 오류 및/또는 어설션 오류가 발생합니다. 항상 이 클래스를 [System::SmartPtr](../system/smartptr/) 포인터로 감싸고 해당 포인터를 인수로 함수에 전달하십시오. |
| [IEnumeratorImplRefType](./ienumeratorimplreftype/) | 제네릭 Iterator [IEnumeratorImplRefType](./ienumeratorimplreftype/) 위에 비제네릭 [IEnumerator](./ienumerator/) 구현을 생성하는 래퍼이며, 참조 타입용 래퍼입니다. |
| [IEnumeratorImplValueType](./ienumeratorimplvaluetype/) | 제네릭 Iterator [IEnumeratorImplRefType](./ienumeratorimplreftype/) 위에 비제네릭 [IEnumerator](./ienumerator/) 구현을 생성하는 래퍼이며, 값 타입용 래퍼입니다. |
| [IEqualityComparer](./iequalitycomparer/) |  |
| [IList](./ilist/) | [IList](./ilist/)은(는) 인덱스로 개별 접근이 가능한 객체들의 비제네릭 컬렉션을 나타냅니다. |
| [IListImplRefType](./ilistimplreftype/) | [System::Collections::Generic::List](../system.collections.generic/list/) 객체에 [System::Collections::IList](./ilist/) 인터페이스를 구현하는 스텁이며, 참조 타입용 구현입니다. |
| [IListImplValueType](./ilistimplvaluetype/) | [System::Collections::Generic::List](../system.collections.generic/list/) 객체에 [System::Collections::IList](./ilist/) 인터페이스를 구현하는 스텁이며, 값 타입용 구현입니다. |
| [IListWrapper](./ilistwrapper/) | 제네릭 컬렉션에서 비제네릭 컬렉션으로 캐스팅을 지원하는 인터페이스입니다. |
| [Invalidatable](./invalidatable/) | [InvalidatableTracker](./invalidatabletracker/) 객체를 통해 하위 객체들의 상태를 추적할 수 있게 하는 클래스입니다. |
| [InvalidatableTracker](./invalidatabletracker/) | [Invalidatable](./invalidatable/) 객체의 트래커를 구현하는 클래스입니다.