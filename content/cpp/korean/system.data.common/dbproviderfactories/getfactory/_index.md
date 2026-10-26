---
title: GetFactory()
second_title: Aspose.Slides C++ API 레퍼런스
description: 이름으로 DB 프로바이더 팩터리를 가져옵니다.
type: docs
weight: 1
url: /ko/system.data.common/dbproviderfactories/getfactory/
---
## DbProviderFactories::GetFactory(const String\&) 메서드

이름으로 DB 프로바이더 팩터리를 가져옵니다.

```cpp
static SharedPtr<DbProviderFactory> System::Data::Common::DbProviderFactories::GetFactory(const String &providerInvariantName)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| providerInvariantName | const [String](../../../system/string/)\& | 프로바이더 이름 (예: 데이터베이스 공급업체 이름). |

### 반환값

프로바이더 팩터리.

## 참고

* 타입정의 [SharedPtr](../../../system/sharedptr/)
* 클래스 [DbProviderFactory](../../dbproviderfactory/)
* 클래스 [String](../../../system/string/)
* 클래스 [DbProviderFactories](../)
* 네임스페이스 [System::Data::Common](../../)
* 라이브러리 [Aspose.Slides](../../../)