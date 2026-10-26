---
title: idx_get()
second_title: Aspose.Slides for C++ API 참조
description: 이름이 지정된 항목을 가져옵니다.
type: docs
weight: 1
url: /ko/system.data.common/dbdatareader/idx_get/
---
## DbDataReader::idx_get(String) 메서드

이름이 지정된 항목을 가져옵니다.

```cpp
virtual SharedPtr<Object> System::Data::Common::DbDataReader::idx_get(String name)=0
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| name | [String](../../../system/string/) | 항목 이름. |

### 반환 값

박스화된 항목 값.

## DbDataReader::idx_get(int) 메서드

인덱스로 항목을 가져옵니다.

```cpp
virtual SharedPtr<Object> System::Data::Common::DbDataReader::idx_get(int ordinal)=0
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| ordinal | int | 항목 인덱스. |

### 반환 값

박스화된 항목 값.

## 참고

* 타입 정의 [SharedPtr](../../../system/sharedptr/)
* 클래스 [Object](../../../system/object/)
* 클래스 [String](../../../system/string/)
* 클래스 [DbDataReader](../)
* 네임스페이스 [System::Data::Common](../../)
* 라이브러리 [Aspose.Slides](../../../)