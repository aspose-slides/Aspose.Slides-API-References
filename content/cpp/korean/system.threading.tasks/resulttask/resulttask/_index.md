---
title: ResultTask()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 값을 반환하는 함수를 사용하여 ResultTask를 생성합니다.
type: docs
weight: 1
url: /ko/system.threading.tasks/resulttask/resulttask/
---
## ResultTask::ResultTask(const Func\<T\>\&) 생성자

[ResultTask](../)을(를) 반환 값을 반환하는 함수와 함께 생성합니다.

```cpp
System::Threading::Tasks::ResultTask<T>::ResultTask(const Func<T> &function)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| function | const [Func](../../../system/func/)\<T\>\& | 결과를 반환하는 비동기 실행 함수 |

## ResultTask::ResultTask() 생성자

내부 구현입니다. 사용자 코드용이 아닙니다.

```cpp
System::Threading::Tasks::ResultTask<T>::ResultTask()
```

## 비고

초기화되지 않은 결과 작업을 만들기 위한 내부 생성자 

## ResultTask::ResultTask(const T\&) 생성자

지정된 결과와 함께 결과 작업을 만들기 위한 내부 생성자.

```cpp
System::Threading::Tasks::ResultTask<T>::ResultTask(const T &result)
```

## 참조

* 클래스 [Func](../../../system/func/)
* 클래스 [ResultTask](../)
* 네임스페이스 [System::Threading::Tasks](../../)
* 라이브러리 [Aspose.Slides](../../../)