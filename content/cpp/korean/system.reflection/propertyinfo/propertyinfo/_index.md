---
title: PropertyInfo()
second_title: Aspose.Slides for C++ API 참조
description: 생성자. const getter만 있는 속성.
type: docs
weight: 66
url: /ko/system.reflection/propertyinfo/propertyinfo/
---
## PropertyInfo::PropertyInfo(String, System::SharedPtr\<PropertyType\>(ClassType::*)() const) 생성자

생성자. const getter만 있는 속성.

```cpp
template<class PropertyType,typename ClassType> System::Reflection::PropertyInfo::PropertyInfo(String name, System::SharedPtr<PropertyType>(ClassType::*get_prop_method)() const)
```

### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| PropertyType | 속성의 타입. |
| ClassType | 속성이 속한 클래스의 타입. |

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| name | [String](../../../system/string/) | 속성 이름. |
| get_prop_method | [System::SharedPtr](../../../system/sharedptr/)\<PropertyType\>(ClassType::*)() const | getter 메서드. |

## PropertyInfo::PropertyInfo(String, System::SharedPtr\<PropertyType\>(ClassType::*)()) 생성자

생성자. non-const getter만 있는 속성.

```cpp
template<class PropertyType,typename ClassType> System::Reflection::PropertyInfo::PropertyInfo(String name, System::SharedPtr<PropertyType>(ClassType::*get_prop_method)())
```

### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| PropertyType | 속성의 타입. |
| ClassType | 속성이 속한 클래스의 타입. |

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| name | [String](../../../system/string/) | 속성 이름. |
| get_prop_method | [System::SharedPtr](../../../system/sharedptr/)\<PropertyType\>(ClassType::*)() | getter 메서드. |

## PropertyInfo::PropertyInfo(String, void(ClassType::*)(System::SharedPtr\<PropertyType\>), System::SharedPtr\<PropertyType\>(ClassType::*)() const) 생성자

생성자.

```cpp
template<class PropertyType,typename ClassType> System::Reflection::PropertyInfo::PropertyInfo(String name, void(ClassType::*set_prop_method)(System::SharedPtr<PropertyType>), System::SharedPtr<PropertyType>(ClassType::*get_prop_method)() const)
```

### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| PropertyType | 속성의 타입. |
| ClassType | 속성이 속한 클래스의 타입. |

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| name | [String](../../../system/string/) | 속성 이름. |
| set_prop_method | void(ClassType::*)([System::SharedPtr](../../../system/sharedptr/)\<PropertyType\>) | setter 메서드. |
| get_prop_method | [System::SharedPtr](../../../system/sharedptr/)\<PropertyType\>(ClassType::*)() const | getter 메서드. |

## PropertyInfo::PropertyInfo(String, void(ClassType::*)(System::Nullable\<NullableType\>), System::Nullable\<NullableType\>(ClassType::*)()) 생성자

생성자. [Nullable](../../../system/nullable/) 속성 (setter와 getter 포함).

```cpp
template<class NullableType,typename ClassType> System::Reflection::PropertyInfo::PropertyInfo(String name, void(ClassType::*set_prop_method)(System::Nullable<NullableType>), System::Nullable<NullableType>(ClassType::*get_prop_method)())
```

### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| PropertyType | 속성의 타입. |
| ClassType | 속성이 속한 클래스의 타입. |

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| name | [String](../../../system/string/) | 속성 이름. |
| set_prop_method | void(ClassType::*)([System::Nullable](../../../system/nullable/)\<NullableType\>) | setter 메서드. |
| get_prop_method | [System::Nullable](../../../system/nullable/)\<NullableType\>(ClassType::*)() | getter 메서드. |

## PropertyInfo::PropertyInfo(String, void(ClassType::*)(System::Nullable\<NullableType\>), System::Nullable\<NullableType\>(ClassType::*)() const) 생성자

생성자. [Nullable](../../../system/nullable/) 속성 (const getter만).

```cpp
template<class NullableType,typename ClassType> System::Reflection::PropertyInfo::PropertyInfo(String name, void(ClassType::*set_prop_method)(System::Nullable<NullableType>), System::Nullable<NullableType>(ClassType::*get_prop_method)() const)
```

### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| PropertyType | 속성의 타입. |
| ClassType | 속성이 속한 클래스의 타입. |

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| name | [String](../../../system/string/) | 속성 이름. |
| set_prop_method | void(ClassType::*)([System::Nullable](../../../system/nullable/)\<NullableType\>) | setter 메서드. |
| get_prop_method | [System::Nullable](../../../system/nullable/)\<NullableType\>(ClassType::*)() const | getter 메서드. |

## PropertyInfo::PropertyInfo(String, void(ClassType::*)(System::SharedPtr\<PropertyType\>), System::SharedPtr\<PropertyType\>(ClassType::*)()) 생성자

생성자. [Object](../../../system/object/) 속성 (getter만).

```cpp
template<class PropertyType,typename ClassType> System::Reflection::PropertyInfo::PropertyInfo(String name, void(ClassType::*set_prop_method)(System::SharedPtr<PropertyType>), System::SharedPtr<PropertyType>(ClassType::*get_prop_method)())
```

### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| PropertyType | 속성의 타입. |
| ClassType | 속성이 속한 클래스의 타입. |

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| name | [String](../../../system/string/) | 속성 이름. |
| set_prop_method | void(ClassType::*)([System::SharedPtr](../../../system/sharedptr/)\<PropertyType\>) | setter 메서드. |
| get_prop_method | [System::SharedPtr](../../../system/sharedptr/)\<PropertyType\>(ClassType::*)() | getter 메서드. |

## PropertyInfo::PropertyInfo(String, void(ClassType::*)(System::String), System::String(ClassType::*)()) 생성자

문자열 속성 정보를 생성합니다.

```cpp
template<typename ClassType> System::Reflection::PropertyInfo::PropertyInfo(String name, void(ClassType::*set_prop_method)(System::String), System::String(ClassType::*get_prop_method)())
```

### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| ClassType | 속성이 속한 클래스의 타입. |

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| name | [String](../../../system/string/) | 속성 이름. |
| set_prop_method | void(ClassType::*)([System::String](../../../system/string/)) | setter 메서드. |
| get_prop_method | [System::String](../../../system/string/)(ClassType::*)() | getter 메서드. |

## PropertyInfo::PropertyInfo(String, void(ClassType::*)(System::String), System::String(ClassType::*)() const) 생성자

const getter가 있는 클래스로부터 문자열 속성 정보를 생성합니다.

```cpp
template<typename ClassType> System::Reflection::PropertyInfo::PropertyInfo(String name, void(ClassType::*set_prop_method)(System::String), System::String(ClassType::*get_prop_method)() const)
```

### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| ClassType | 속성이 속한 클래스의 타입. |

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| name | [String](../../../system/string/) | 속성 이름. |
| set_prop_method | void(ClassType::*)([System::String](../../../system/string/)) | setter 메서드. |
| get_prop_method | [System::String](../../../system/string/)(ClassType::*)() const | getter 메서드. |

## PropertyInfo::PropertyInfo(String, void(ClassType::*)(System::Decimal), System::Decimal(ClassType::*)()) 생성자

[Decimal](../../../system/decimal/) 속성 정보를 생성합니다.

```cpp
template<typename ClassType> System::Reflection::PropertyInfo::PropertyInfo(String name, void(ClassType::*set_prop_method)(System::Decimal), System::Decimal(ClassType::*get_prop_method)())
```

### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| ClassType | 속성이 속한 클래스의 타입. |

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| name | [String](../../../system/string/) | 속성 이름. |
| set_prop_method | void(ClassType::*)([System::Decimal](../../../system/decimal/)) | setter 메서드. |
| get_prop_method | [System::Decimal](../../../system/decimal/)(ClassType::*)() | getter 메서드. |

## PropertyInfo::PropertyInfo(String, void(ClassType::*)(System::Decimal), System::Decimal(ClassType::*)() const) 생성자

const getter가 있는 클래스로부터 [Decimal](../../../system/decimal/) 속성 정보를 생성합니다.

```cpp
template<typename ClassType> System::Reflection::PropertyInfo::PropertyInfo(String name, void(ClassType::*set_prop_method)(System::Decimal), System::Decimal(ClassType::*get_prop_method)() const)
```

### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| ClassType | 속성이 속한 클래스의 타입. |

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| name | [String](../../../system/string/) | 속성 이름. |
| set_prop_method | void(ClassType::*)([System::Decimal](../../../system/decimal/)) | setter 메서드. |
| get_prop_method | [System::Decimal](../../../system/decimal/)(ClassType::*)() const | getter 메서드. |

## PropertyInfo::PropertyInfo(String, void(ClassType::*)(bool), bool(ClassType::*)()) 생성자

불리언 속성 정보를 생성합니다.

```cpp
template<typename ClassType> System::Reflection::PropertyInfo::PropertyInfo(String name, void(ClassType::*set_prop_method)(bool), bool(ClassType::*get_prop_method)())
```

### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| ClassType | 속성이 속한 클래스의 타입. |

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| name | [String](../../../system/string/) | 속성 이름. |
| set_prop_method | void(ClassType::*)(**bool**) | setter 메서드. |
| get_prop_method | **bool**(ClassType::*)() | getter 메서드. |

## PropertyInfo::PropertyInfo(String, void(ClassType::*)(bool), bool(ClassType::*)() const) 생성자

const getter가 있는 클래스로부터 불리언 속성 정보를 생성합니다.

```cpp
template<typename ClassType> System::Reflection::PropertyInfo::PropertyInfo(String name, void(ClassType::*set_prop_method)(bool), bool(ClassType::*get_prop_method)() const)
```

### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| ClassType | 속성이 속한 클래스의 타입. |

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| name | [String](../../../system/string/) | 속성 이름. |
| set_prop_method | void(ClassType::*)(**bool**) | setter 메서드. |
| get_prop_method | **bool**(ClassType::*)() const | getter 메서드. |

## PropertyInfo::PropertyInfo(String, void(ClassType::*)(int64_t), int64_t(ClassType::*)()) 생성자

**int64_t** 속성 정보를 생성합니다.

```cpp
template<typename ClassType> System::Reflection::PropertyInfo::PropertyInfo(String name, void(ClassType::*set_prop_method)(int64_t), int64_t(ClassType::*get_prop_method)())
```

### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| ClassType | 속성이 속한 클래스의 타입. |

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| name | [String](../../../system/string/) | 속성 이름. |
| set_prop_method | void(ClassType::*)(**int64_t**) | setter 메서드. |
| get_prop_method | **int64_t**(ClassType::*)() | getter 메서드. |

## PropertyInfo::PropertyInfo(String, void(ClassType::*)(int64_t), int64_t(ClassType::*)() const) 생성자

const getter가 있는 클래스로부터 **int64_t** 속성 정보를 생성합니다.

```cpp
template<typename ClassType> System::Reflection::PropertyInfo::PropertyInfo(String name, void(ClassType::*set_prop_method)(int64_t), int64_t(ClassType::*get_prop_method)() const)
```

### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| ClassType | 속성이 속한 클래스의 타입. |

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| name | [String](../../../system/string/) | 속성 이름. |
| set_prop_method | void(ClassType::*)(**int64_t**) | setter 메서드. |
| get_prop_method | **int64_t**(ClassType::*)() const | getter 메서드. |

## 참고

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [String](../../../system/string/)
* Class [PropertyInfo](../)
* Class [Nullable](../../../system/nullable/)
* Class [Decimal](../../../system/decimal/)
* Namespace [System::Reflection](../../)
* Library [Aspose.Slides](../../../)