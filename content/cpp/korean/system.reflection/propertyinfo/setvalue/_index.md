---
title: SetValue()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 특정 객체에 속성 값을 설정합니다.
type: docs
weight: 14
url: /ko/system.reflection/propertyinfo/setvalue/
---
## PropertyInfo::SetValue(System::SharedPtr\<System::Object\>, System::SharedPtr\<System::Object\>) method

특정 객체에 속성 값을 설정합니다.

```cpp
void System::Reflection::PropertyInfo::SetValue(System::SharedPtr<System::Object> obj, System::SharedPtr<System::Object> value)
```

### 인수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| obj | [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\> | [Object](../../../system/object/)에 속성을 씁니다. |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\> | 설정할 속성 값. |

## PropertyInfo::SetValue(System::SharedPtr\<System::Object\>, System::SharedPtr\<System::Object\>, System::ArrayPtr\<System::SharedPtr\<System::Object\>\>) method

특정 객체에 속성 값을 설정합니다.

```cpp
void System::Reflection::PropertyInfo::SetValue(System::SharedPtr<System::Object> obj, System::SharedPtr<System::Object> value, System::ArrayPtr<System::SharedPtr<System::Object>> indexer)
```

### 인수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| obj | [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\> | [Object](../../../system/object/)에 속성을 씁니다. |
| indexer | [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\> | 인덱스가 있는 속성의 경우 선택적인 인덱스 값입니다. 인덱스가 없는 속성의 경우 이 값은 null이어야 합니다. |
| value | [System::ArrayPtr](../../../system/arrayptr/)\<[System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\>\> | 설정할 속성 값. |

## 참고

* 타입 정의 [SharedPtr](../../../system/sharedptr/)
* 타입 정의 [ArrayPtr](../../../system/arrayptr/)
* 클래스 [Object](../../../system/object/)
* 클래스 [PropertyInfo](../)
* 네임스페이스 [System::Reflection](../../)
* 라이브러리 [Aspose.Slides](../../../)