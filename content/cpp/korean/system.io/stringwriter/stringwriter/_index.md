---
title: StringWriter()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 지정된 StringBuilder와 IFormatProvider를 사용하여 StringWriter의 새 인스턴스를 생성합니다.
type: docs
weight: 1
url: /ko/system.io/stringwriter/stringwriter/
---
## StringWriter::StringWriter(const System::SharedPtr\<Text::StringBuilder\>\&, const IFormatProviderPtr\&) 생성자

[StringWriter](../)의 새 인스턴스를 지정된 StringBuilder와 [IFormatProvider](../../../system/iformatprovider/)를 사용하여 생성합니다.

```cpp
System::IO::StringWriter::StringWriter(const System::SharedPtr<Text::StringBuilder> &sb, const IFormatProviderPtr &formatProvider)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| sb | const [System::SharedPtr](../../../system/sharedptr/)\<[Text::StringBuilder](../../../system.text/stringbuilder/)\>\& | [StringWriter](../)가 생성될 때 사용할 StringBuilder 객체 |
| formatProvider | const [IFormatProviderPtr](../../../system/iformatproviderptr/)\& | 생성되는 객체가 사용할 [IFormatProvider](../../../system/iformatprovider/) 객체 |

## StringWriter::StringWriter(const System::SharedPtr\<Text::StringBuilder\>\&) 생성자

[StringWriter](../)의 새 인스턴스를 지정된 StringBuilder와 현재 문화권의 [IFormatProvider](../../../system/iformatprovider/)를 사용하여 생성합니다.

```cpp
System::IO::StringWriter::StringWriter(const System::SharedPtr<Text::StringBuilder> &sb)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| sb | const [System::SharedPtr](../../../system/sharedptr/)\<[Text::StringBuilder](../../../system.text/stringbuilder/)\>\& | [StringWriter](../)가 생성될 때 사용할 StringBuilder 객체 |

## StringWriter::StringWriter(const IFormatProviderPtr\&) 생성자

[StringWriter](../)의 새 인스턴스를 지정된 [IFormatProvider](../../../system/iformatprovider/)를 사용하여 생성합니다.

```cpp
System::IO::StringWriter::StringWriter(const IFormatProviderPtr &formatProvider)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| formatProvider | const [IFormatProviderPtr](../../../system/iformatproviderptr/)\& | 생성되는 객체가 사용할 [IFormatProvider](../../../system/iformatprovider/) 객체 |

## StringWriter::StringWriter() 생성자

[StringWriter](../)의 새 인스턴스를 현재 문화권의 [IFormatProvider](../../../system/iformatprovider/)를 사용하여 생성합니다.

```cpp
System::IO::StringWriter::StringWriter()
```

## 참고

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [IFormatProviderPtr](../../../system/iformatproviderptr/)
* Class [StringBuilder](../../../system.text/stringbuilder/)
* Class [StringWriter](../)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)