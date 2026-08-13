---
title: MakeObject()
second_title: Aspose.Slides for C++ API 참조
description: 힙에 객체를 생성하고 해당 객체에 대한 공유 포인터를 반환합니다.
type: docs
weight: 2887
url: /ko/system/makeobject/
---
## System::MakeObject(Args\&&...) 함수


힙에 객체를 생성하고 해당 객체에 대한 공유 포인터를 반환합니다.

```cpp
template<class T,class ...> std::enable_if<!IsSmartPtr<T>::value, SmartPtr<T>>::type System::MakeObject(Args &&... args)
```


### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| T | 인스턴스화할 클래스. |
| Args | 생성자 인수의 형식. |

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| args | Args\&&... | 생성자 인수. |

### 반환 값

[SmartPtr](../smartptr/) 새로 만든 객체에 대한 포인터, 항상 공유 모드로 반환됩니다.

## System::MakeObject(Args\&&...) 함수


힙에 객체를 생성하고 해당 객체에 대한 공유 포인터를 반환합니다.

```cpp
template<class T,class ...> std::enable_if<IsSmartPtr<T>::value, T>::type System::MakeObject(Args &&... args)
```


### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| T | [SmartPtr](../smartptr/) 인스턴스화할 클래스. |
| Args | 생성자 인수의 형식. |

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| args | Args\&&... | 생성자 인수. |

### 반환 값

[SmartPtr](../smartptr/) 새로 만든 객체에 대한 포인터, 항상 공유 모드로 반환됩니다.

## 참고

* 클래스 [SmartPtr](../smartptr/)
* 구조체 [IsSmartPtr](../issmartptr/)
* 네임스페이스 [System](../)
* 라이브러리 [Aspose.Slides](../../)