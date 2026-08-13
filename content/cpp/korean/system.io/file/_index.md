---
title: File
second_title: Aspose.Slides for C++ API 레퍼런스
description: 파일을 조작하기 위한 메서드를 제공합니다. 이는 인스턴스 서비스가 없는 정적 타입입니다. 어떠한 방식으로도 인스턴스를 생성해서는 안 됩니다.
type: docs
weight: 261
url: /ko/system.io/file/
---
## File 클래스

파일을 조작하기 위한 메서드를 제공합니다. 이는 인스턴스 서비스가 없는 정적 타입입니다. 어떠한 방식으로도 인스턴스를 생성해서는 안 됩니다.

```cpp
class File
```

## 메서드

| 메서드 | 설명 |
| --- | --- |
| static void [AppendAllLines](./appendalllines/)(const [String](../../system/string/)\&, const [SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IEnumerable](../../system.collections.generic/ienumerable/)\<[String](../../system/string/)\>\>\&, const [EncodingPtr](../../system/encodingptr/)\&) | 지정된 문자열 컬렉션에 있는 문자열을 지정된 인코딩을 사용하여 각 문자열을 새로운 줄에 기록함으로써 지정된 파일에 추가합니다. 지정된 파일이 존재하지 않으면 생성됩니다. 모든 문자열을 기록한 후 파일이 닫힙니다. |
| static void [AppendAllText](./appendalltext/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [EncodingPtr](../../system/encodingptr/)\&) | 지정된 문자열을 지정된 인코딩을 사용하여 지정된 파일에 추가합니다. |
| static [StreamWriterPtr](../../system/streamwriterptr/) [AppendText](./appendtext/)(const [String](../../system/string/)\&) | [StreamWriter](../streamwriter/) 객체를 생성하여 UTF-8 인코딩을 사용해 지정된 파일에 텍스트를 추가합니다. 지정된 파일이 존재하지 않으면 생성됩니다. |
| static void [Copy](./copy/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, **bool**) | 지정된 파일을 지정된 위치로 복사합니다. 대상 파일이 이미 존재하는 경우, 매개변수를 통해 덮어쓸지 여부를 지정합니다. |
| static [FileStreamPtr](../../system/filestreamptr/) [Create](./create/)(const [String](../../system/string/)\&, **int32_t**, [FileOptions](../fileoptions/)) | 새 파일을 생성(또는 기존 파일을 덮어쓰기)하고 지정된 버퍼 크기와 옵션을 사용하여 읽기 및 쓰기 액세스로 엽니다. |
| static [StreamWriterPtr](../../system/streamwriterptr/) [CreateText](./createtext/)(const [String](../../system/string/)\&) | UTF-8 인코딩된 텍스트를 쓰기 위해 새 파일을 생성하거나 기존 파일을 엽니다. |
| static void [Decrypt](./decrypt/)(const [String](../../system/string/)\&) | NOT IMPLEMENTED. |
| static void [Delete](./delete/)(const [String](../../system/string/)\&) | 지정된 파일 또는 디렉터리를 삭제합니다. |
| static void [Encrypt](./encrypt/)(const [String](../../system/string/)\&) | NOT IMPLEMENTED. |
| static **bool** [Exists](./exists/)(const [String](../../system/string/)\&) | 지정된 경로가 기존 파일을 가리키는지 확인합니다. |
| static [FileAttributes](../fileattributes/) [GetAttributes](./getattributes/)(const [String](../../system/string/)\&) | 지정된 엔터티의 속성을 반환합니다. |
| static [DateTime](../../system/datetime/) [GetCreationTime](./getcreationtime/)(const [String](../../system/string/)\&) | 지정된 엔터티의 생성 시간을 로컬 시간으로 반환합니다. |
| static [DateTime](../../system/datetime/) [GetCreationTimeUtc](./getcreationtimeutc/)(const [String](../../system/string/)\&) | 지정된 엔터티의 생성 시간을 UTC 시간으로 반환합니다. |
| static [DateTime](../../system/datetime/) [GetLastAccessTime](./getlastaccesstime/)(const [String](../../system/string/)\&) | 지정된 엔터티의 마지막 액세스 시간을 로컬 시간으로 반환합니다. |
| static [DateTime](../../system/datetime/) [GetLastAccessTimeUtc](./getlastaccesstimeutc/)(const [String](../../system/string/)\&) | 지정된 엔터티의 마지막 액세스 시간을 UTC 시간으로 반환합니다. |
| static [DateTime](../../system/datetime/) [GetLastWriteTime](./getlastwritetime/)(const [String](../../system/string/)\&) | 지정된 엔터티의 마지막 쓰기 시간을 로컬 시간으로 반환합니다. |
| static [DateTime](../../system/datetime/) [GetLastWriteTimeUtc](./getlastwritetimeutc/)(const [String](../../system/string/)\&) | 지정된 엔터티의 마지막 쓰기 시간을 UTC 시간으로 반환합니다. |
| static void [Move](./move/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | 지정된 파일을 새 위치로 이동합니다. |
| static [FileStreamPtr](../../system/filestreamptr/) [Open](./open/)(const [String](../../system/string/)\&, [FileMode](../filemode/)) | 지정된 파일을 지정된 모드로 읽기와 쓰기를 위해 열며 공유를 허용하지 않습니다. |
| static [FileStreamPtr](../../system/filestreamptr/) [Open](./open/)(const [String](../../system/string/)\&, [FileMode](../filemode/), [FileAccess](../fileaccess/), [FileShare](../fileshare/)) | 지정된 파일을 지정된 모드와 접근 유형 및 공유 옵션으로 엽니다. |
| static [FileStreamPtr](../../system/filestreamptr/) [OpenRead](./openread/)(const [String](../../system/string/)\&) | 읽기 전용으로 지정된 파일을 'Open' 모드에서 읽기 공유 액세스로 엽니다. |
| static [StreamReaderPtr](../../system/streamreaderptr/) [OpenText](./opentext/)(const [String](../../system/string/)\&, const [EncodingPtr](../../system/encodingptr/)\&) | UTF-8 인코딩을 사용하여 지정된 기존 파일을 텍스트 읽기 전용으로 열고 공유를 허용하지 않습니다. |
| static [FileStreamPtr](../../system/filestreamptr/) [OpenWrite](./openwrite/)(const [String](../../system/string/)\&) | 쓰기 전용으로 지정된 파일을 'OpenOrCreate' 모드에서 열고 공유를 허용하지 않습니다. |
| static [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [ReadAllBytes](./readallbytes/)(const [String](../../system/string/)\&) | 지정된 바이너리 파일의 내용을 바이트 배열로 읽어옵니다. |
| static [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\> [ReadAllLines](./readalllines/)(const [String](../../system/string/)\&, const [EncodingPtr](../../system/encodingptr/)\&) | 지정된 문자 인코딩을 사용하여 지정된 텍스트 파일의 내용을 줄별로 문자열 배열에 읽어옵니다. |
| static [String](../../system/string/) [ReadAllText](./readalltext/)(const [String](../../system/string/)\&, const [EncodingPtr](../../system/encodingptr/)\&) | 지정된 문자 인코딩을 사용하여 지정된 텍스트 파일의 내용을 단일 [String](../../system/string/) 객체로 읽어옵니다. |
| static [SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IEnumerable](../../system.collections.generic/ienumerable/)\<[String](../../system/string/)\>\> [ReadLines](./readlines/)(const [String](../../system/string/)\&, const [EncodingPtr](../../system/encodingptr/)\&) | 지정된 문자 인코딩을 사용하여 지정된 텍스트 파일의 내용을 줄별로 읽어들이고, 파일 내용의 각 줄을 나타내는 문자열 컬렉션을 반환합니다. |
| static void [Replace](./replace/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&, **bool**) | 하나의 파일 내용을 다른 파일로 교체하고 교체된 파일의 백업을 생성합니다. |
| static void [SetAttributes](./setattributes/)(const [String](../../system/string/)\&, [FileAttributes](../fileattributes/)) | 지정된 파일에 지정된 속성을 설정합니다. |
| static void [SetCreationTime](./setcreationtime/)(const [String](../../system/string/)\&, [DateTime](../../system/datetime/)) | NOT IMPLEMENTED. |
| static void [SetCreationTimeUtc](./setcreationtimeutc/)(const [String](../../system/string/)\&, [DateTime](../../system/datetime/)) | NOT IMPLEMENTED. |
| static void [SetLastAccessTime](./setlastaccesstime/)(const [String](../../system/string/)\&, [DateTime](../../system/datetime/)) | NOT IMPLEMENTED. |
| static void [SetLastAccessTimeUtc](./setlastaccesstimeutc/)(const [String](../../system/string/)\&, [DateTime](../../system/datetime/)) | NOT IMPLEMENTED. |
| static void [SetLastWriteTime](./setlastwritetime/)(const [String](../../system/string/)\&, [DateTime](../../system/datetime/)) | 지정된 엔터티의 마지막 쓰기 시간을 로컬 시간으로 설정합니다. |
| static void [SetLastWriteTimeUtc](./setlastwritetimeutc/)(const [String](../../system/string/)\&, [DateTime](../../system/datetime/)) | 지정된 엔터티의 마지막 쓰기 시간을 UTC 시간으로 설정합니다. |
| static void [WriteAllBytes](./writeallbytes/)(const [String](../../system/string/)\&, const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&) | 지정된 바이너리 파일을 덮어쓰고 지정된 바이트를 기록합니다. |
| static void [WriteAllLines](./writealllines/)(const [String](../../system/string/)\&, const [SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IEnumerable](../../system.collections.generic/ienumerable/)\<[String](../../system/string/)\>\>\&, const [EncodingPtr](../../system/encodingptr/)\&) | 새 텍스트 파일을 생성하거나 기존 파일을 덮어쓰고, 지정된 인코딩을 사용하여 지정된 문자열 컬렉션의 모든 문자열을 각 줄에 하나씩 기록합니다. |
| static void [WriteAllLines](./writealllines/)(const [String](../../system/string/)\&, const [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\>\&, const [EncodingPtr](../../system/encodingptr/)\&) | 새 텍스트 파일을 생성하거나 기존 파일을 덮어쓰고, 지정된 인코딩을 사용하여 지정된 문자열 배열의 모든 문자열을 각 줄에 하나씩 기록합니다. |
| static void [WriteAllText](./writealltext/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [EncodingPtr](../../system/encodingptr/)\&) | 새 텍스트 파일을 생성하거나 기존 파일을 덮어쓰고, 지정된 인코딩을 사용하여 지정된 문자열의 내용을 기록합니다. |

## 필드

| 필드 | 설명 |
| --- | --- |
| static [DefaultBufferSize](./defaultbuffersize/) | 파일을 읽고 쓸 때 버퍼링되는 바이트 수의 기본값입니다. |

## 관련 항목

* 네임스페이스 [System::IO](../)
* 라이브러리 [Aspose.Slides](../../)