---
title: GetValue()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 특정 객체에서 속성 값을 가져옵니다.
type: docs
weight: 1
url: /ko/system.reflection/propertyinfo/getvalue/
---
## PropertyInfo::GetValue(System::SharedPtr\<System::Object\>) 메서드

특정 객체에서 속성 값을 가져옵니다.

```cpp
System::SharedPtr<System::Object> System::Reflection::PropertyInfo::GetValue(System::SharedPtr<System::Object> obj)
```

### 인수

| Parameter | Type | Description |
| --- | --- | --- |
| obj | [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\> | [Object](../../../system/object/) 속성을 읽을 객체. |

### 반환값

지정된 객체의 지정된 속성 값.

## PropertyInfo::GetValue(System::SharedPtr\<System::Object\>, System::ArrayPtr\<System::SharedPtr\<System::Object\>\>) 메서드

특정 객체에서 속성 값을 가져옵니다.

```cpp
System::SharedPtr<System::Object> System::Reflection::PropertyInfo::GetValue(System::SharedPtr<System::Object> obj, System::ArrayPtr<System::SharedPtr<System::Object>> indexer)
```

### 인수

| Parameter | Type | Description |
| --- | --- | --- |
| obj | [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\> | [Object](../../../system/object/) 속성을 읽을 객체. |
| indexer | [System::ArrayPtr](../../../system/arrayptr/)\<[System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\>\> | 이것은 인덱스가 있는 속성에 대한 선택적 인덱스 값입니다. 인덱스가 없는 속성의 경우, 이 값은 null이어야 합니다. |

### 반환값

지정된 객체의 지정된 속성 값.

## 참조

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* 클래스 [Object](../../../system/object/)
* 클래스 [PropertyInfo](../)
* 네임스페이스 [System::Reflection](../../)
* 라이브러리 [Aspose.Slides](../../../)