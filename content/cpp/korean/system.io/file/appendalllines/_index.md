---
title: AppendAllLines()
second_title: Aspose.Slides C++ API 참조
description: 지정된 문자열 컬렉션에서 문자열을 가져와 지정된 인코딩을 사용하여 각 문자열을 새 행에 기록함으로써 지정된 파일에 추가합니다. 지정된 파일이 존재하지 않을 경우 파일이 생성됩니다. 모든 문자열을 기록한 후 파일이 닫힙니다.
type: docs
weight: 1
url: /ko/system.io/file/appendalllines/
---
## File::AppendAllLines(const String\&, const SharedPtr\<Collections::Generic::IEnumerable\<String\>\>\&, const EncodingPtr\&) method


지정된 문자열 컬렉션에서 문자열을 가져와 지정된 인코딩을 사용하여 각 문자열을 새 행에 기록함으로써 지정된 파일에 추가합니다. 지정된 파일이 존재하지 않을 경우 파일이 생성됩니다. 모든 문자열을 기록한 후 파일이 닫힙니다.

```cpp
static void System::IO::File::AppendAllLines(const String &path, const SharedPtr<Collections::Generic::IEnumerable<String>> &contents, const EncodingPtr &encoding=Text::Encoding::get_UTF8Unmarked())
```


### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | 문자열을 추가할 파일의 경로 |
| contents | const [SharedPtr](../../../system/sharedptr/)\<[Collections::Generic::IEnumerable](../../../system.collections.generic/ienumerable/)\<[String](../../../system/string/)\>\>\& | 파일에 기록할 문자열 |
| encoding | const [EncodingPtr](../../../system/encodingptr/)\& | 사용할 문자 인코딩 |

## 참조

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [EncodingPtr](../../../system/encodingptr/)
* 클래스 [String](../../../system/string/)
* 클래스 [IEnumerable](../../../system.collections.generic/ienumerable/)
* 클래스 [File](../)
* 네임스페이스 [System::IO](../../)
* Library [Aspose.Slides](../../../)