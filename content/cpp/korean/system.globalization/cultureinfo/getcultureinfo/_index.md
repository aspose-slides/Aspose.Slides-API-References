---
title: GetCultureInfo()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 이름으로 문화를 가져옵니다. CreateSpecificCulture와 동일합니다.
type: docs
weight: 586
url: /ko/system.globalization/cultureinfo/getcultureinfo/
---
## CultureInfo::GetCultureInfo(const String\&) 메서드

이름으로 문화를 가져옵니다. CreateSpecificCulture와 동일합니다.

```cpp
static CultureInfoPtr System::Globalization::CultureInfo::GetCultureInfo(const String &name)
```

### 매개변수

| Parameter | Type | Description |
| --- | --- | --- |
| name | const [String](../../../system/string/)\& | 미리 정의된 문화 이름 또는 기존 문화 객체의 이름. |

### 반환 값

새롭게 생성된 문화 객체.

## CultureInfo::GetCultureInfo(const String\&, const String\&) 메서드

이름으로 문화를 가져옵니다.

```cpp
static CultureInfoPtr System::Globalization::CultureInfo::GetCultureInfo(const String &name, const String &text_and_compare_culture_name)
```

### 매개변수

| Parameter | Type | Description |
| --- | --- | --- |
| name | const [String](../../../system/string/)\& | 문화 이름. |
| text_and_compare_culture_name | const [String](../../../system/string/)\& | [TextInfo](../../textinfo/) 및 [CompareInfo](../../compareinfo/) 객체에 사용되는 문화 이름. |

### 반환 값

문화 객체.

## CultureInfo::GetCultureInfo(int32_t) 메서드

ID로 문화를 가져옵니다.

```cpp
static CultureInfoPtr System::Globalization::CultureInfo::GetCultureInfo(int32_t culture)
```

### 매개변수

| Parameter | Type | Description |
| --- | --- | --- |
| culture | **int32_t** | 문화 식별자. |

### 반환 값

새롭게 생성된 문화 객체.

## 참고

* Typedef [CultureInfoPtr](../../cultureinfoptr/)
* 클래스 [String](../../../system/string/)
* 클래스 [CultureInfo](../)
* 네임스페이스 [System::Globalization](../../)
* 라이브러리 [Aspose.Slides](../../../)