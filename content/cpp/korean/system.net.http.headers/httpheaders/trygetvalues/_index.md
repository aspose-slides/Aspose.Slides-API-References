---
title: TryGetValues()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 지정된 이름으로 해당 값을 가져오려고 시도합니다.
type: docs
weight: 66
url: /ko/system.net.http.headers/httpheaders/trygetvalues/
---
## HttpHeaders::TryGetValues(String, System::SharedPtr\<Collections::Generic::IEnumerable\<String\>\>\&) 메서드


지정된 이름으로 해당 값을 가져오려고 시도합니다.

```cpp
bool System::Net::Http::Headers::HttpHeaders::TryGetValues(String name, System::SharedPtr<Collections::Generic::IEnumerable<String>> &values)
```


### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| name | [String](../../../system/string/) | 헤더 이름. |
| values | [System::SharedPtr](../../../system/sharedptr/)\<[Collections::Generic::IEnumerable](../../../system.collections.generic/ienumerable/)\<[String](../../../system/string/)\>\>\& | 해당 값이 할당될 인스턴스. |

### 반환값

지정된 이름으로 헤더 값을 찾으면 true, 그렇지 않으면 false.

## 참고

* Typedef [SharedPtr](../../../system/sharedptr/)
* 클래스 [String](../../../system/string/)
* 클래스 [IEnumerable](../../../system.collections.generic/ienumerable/)
* 클래스 [HttpHeaders](../)
* 네임스페이스 [System::Net::Http::Headers](../../)
* 라이브러리 [Aspose.Slides](../../../)