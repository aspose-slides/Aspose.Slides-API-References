---
title: RunWorkerCompletedEventArgs()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 생성자.
type: docs
weight: 1
url: /ko/system.componentmodel/runworkercompletedeventargs/runworkercompletedeventargs/
---
## RunWorkerCompletedEventArgs::RunWorkerCompletedEventArgs(const System::SharedPtr\<System::Object\>\&, const System::Exception\&, bool) 생성자

생성자.

```cpp
System::ComponentModel::RunWorkerCompletedEventArgs::RunWorkerCompletedEventArgs(const System::SharedPtr<System::Object> &result, const System::Exception &error, bool canceled)
```

### 매개변수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| result | const [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\>\& | 비동기 작업의 결과입니다. |
| error | const [System::Exception](../../../system/exception/)\& | 비동기 작업 중에 발생한 오류. |
| canceled | **bool** | 비동기 작업이 취소되었는지 여부를 나타내는 값. |

## 참고

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [Exception](../../../system/exception/)
* 클래스 [Object](../../../system/object/)
* 클래스 [RunWorkerCompletedEventArgs](../)
* 네임스페이스 [System::ComponentModel](../../)
* 라이브러리 [Aspose.Slides](../../../)