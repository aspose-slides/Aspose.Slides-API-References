---
title: Join()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 문자열을 구분자로 사용하여 배열을 결합합니다.
type: docs
weight: 846
url: /ko/system/string/join/
---
## String::Join(const String\&, const ArrayPtr\<String\>\&, int, int) 메서드

문자열을 구분자로 사용하여 배열을 결합합니다.

```cpp
static String System::String::Join(const String &separator, const ArrayPtr<String> &parts, int startIndex=0, int count=-1)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| separator | const [String](../)\& | [String](../)를 배열 요소 사이에 넣을 때 사용합니다. |
| parts | const [ArrayPtr](../../arrayptr/)\<[String](../)\>\& | [Array](../../array/)를 결합할 파트. |
| startIndex | int | 결합을 시작할 배열의 첫 번째 인덱스. |
| count | int | 결합할 배열 요소의 수. -1은 '배열이 끝날 때까지'를 의미합니다. |

### 반환 값

[String](../)는 결합된 배열 요소를 나타냅니다.

## String::Join(const String\&, const System::Details::ArrayView\<String\>\&, int, int) 메서드

문자열을 구분자로 사용하여 배열을 결합합니다.

```cpp
static String System::String::Join(const String &separator, const System::Details::ArrayView<String> &parts, int startIndex=0, int count=-1)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| separator | const [String](../)\& | [String](../)를 배열 요소 사이에 넣을 때 사용합니다. |
| parts | const System::Details::ArrayView\<[String](../)\>\& | 결합할 파트의 ArrayView. |
| startIndex | int | 결합을 시작할 배열의 첫 번째 인덱스. |
| count | int | 결합할 배열 요소의 수. -1은 '배열이 끝날 때까지'를 의미합니다. |

### 반환 값

[String](../)는 결합된 배열 요소를 나타냅니다.

## String::Join(const String\&, const SharedPtr\<System::Collections::Generic::IEnumerable\<String\>\>\&) 메서드

문자열을 구분자로 사용하여 배열을 결합합니다.

```cpp
static String System::String::Join(const String &separator, const SharedPtr<System::Collections::Generic::IEnumerable<String>> &parts)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| separator | const [String](../)\& | [String](../)를 배열 요소 사이에 넣을 때 사용합니다. |
| parts | const [SharedPtr](../../sharedptr/)\<[System::Collections::Generic::IEnumerable](../../../system.collections.generic/ienumerable/)\<[String](../)\>\>\& | - parts 열거 가능 객체 |

### 반환 값

[String](../)는 결합된 요소를 나타냅니다.

## String::Join(const String\&, const ArrayPtr\<SharedPtr\<Object\>\>\&) 메서드

문자열을 구분자로 사용하여 배열을 결합합니다.

```cpp
static String System::String::Join(const String &separator, const ArrayPtr<SharedPtr<Object>> &parts)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| separator | const [String](../)\& | [String](../)를 배열 요소 사이에 넣을 때 사용합니다. |
| parts | const [ArrayPtr](../../arrayptr/)\<[SharedPtr](../../sharedptr/)\<[Object](../../object/)\>\>\& | [Array](../../array/)를 결합할 파트. |

### 반환 값

[String](../)는 결합된 요소를 나타냅니다.

## 참조

* Typedef [ArrayPtr](../../arrayptr/)
* Typedef [SharedPtr](../../sharedptr/)
* 클래스 [String](../)
* 클래스 [IEnumerable](../../../system.collections.generic/ienumerable/)
* 클래스 [Object](../../object/)
* 네임스페이스 [System](../../)
* 라이브러리 [Aspose.Slides](../../../)