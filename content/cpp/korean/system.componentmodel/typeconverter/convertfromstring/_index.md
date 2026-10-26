---
title: ConvertFromString()
second_title: Aspose.Slides C++용 API 레퍼런스
description: 문자열을 객체로 변환합니다.
type: docs
weight: 40
url: /ko/system.componentmodel/typeconverter/convertfromstring/
---
## TypeConverter::ConvertFromString(const System::String\&) 메서드

문자열을 객체로 변환합니다.

```cpp
System::SharedPtr<System::Object> System::ComponentModel::TypeConverter::ConvertFromString(const System::String &text)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| text | const [System::String](../../../system/string/)\& | 변환할 값. |

### 반환값

변환된 객체.

## TypeConverter::ConvertFromString(const System::SharedPtr\<ITypeDescriptorContext\>\&, const System::String\&) 메서드

문자열을 객체로 변환합니다.

```cpp
System::SharedPtr<System::Object> System::ComponentModel::TypeConverter::ConvertFromString(const System::SharedPtr<ITypeDescriptorContext> &context, const System::String &text)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| context | const [System::SharedPtr](../../../system/sharedptr/)\<[ITypeDescriptorContext](../../itypedescriptorcontext/)\>\& | [Object](../../../system/object/) 변환 컨텍스트 정보. |
| text | const [System::String](../../../system/string/)\& | 변환할 값. |

### 반환값

변환된 객체.

## TypeConverter::ConvertFromString(const System::SharedPtr\<ITypeDescriptorContext\>\&, const System::SharedPtr\<System::Globalization::CultureInfo\>\&, const System::String\&) 메서드

문자열을 객체로 변환합니다.

```cpp
System::SharedPtr<System::Object> System::ComponentModel::TypeConverter::ConvertFromString(const System::SharedPtr<ITypeDescriptorContext> &context, const System::SharedPtr<System::Globalization::CultureInfo> &culture, const System::String &text)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| context | const [System::SharedPtr](../../../system/sharedptr/)\<[ITypeDescriptorContext](../../itypedescriptorcontext/)\>\& | [Object](../../../system/object/) 변환 컨텍스트 정보. |
| culture | const [System::SharedPtr](../../../system/sharedptr/)\<[System::Globalization::CultureInfo](../../../system.globalization/cultureinfo/)\>\& | 객체를 변환할 때 사용할 문화권. |
| text | const [System::String](../../../system/string/)\& | 변환할 값. |

### 반환값

변환된 객체.

## 참조

* 타입정의 [SharedPtr](../../../system/sharedptr/)
* 클래스 [Object](../../../system/object/)
* 클래스 [String](../../../system/string/)
* 클래스 [TypeConverter](../)
* 클래스 [ITypeDescriptorContext](../../itypedescriptorcontext/)
* 클래스 [CultureInfo](../../../system.globalization/cultureinfo/)
* 네임스페이스 [System::ComponentModel](../../)
* 라이브러리 [Aspose.Slides](../../../)