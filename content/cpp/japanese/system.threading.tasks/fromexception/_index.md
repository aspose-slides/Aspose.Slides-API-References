---
title: FromException()
second_title: Aspose.Slides for C++ API リファレンス
description: 指定された例外で完了したタスクを作成します。
type: docs
weight: 131
url: /ja/system.threading.tasks/fromexception/
---
## System::Threading::Tasks::FromException(const Exception\&) 関数

指定された例外で完了したタスクを作成します。

```cpp
TaskPtr System::Threading::Tasks::FromException(const Exception &exception)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| exception | const [Exception](../../system/exception/)\& | タスクを完了させる例外です。 |

### 戻り値

失敗したタスクです。

## System::Threading::Tasks::FromException(const Exception\&) 関数

指定された例外と結果の型で完了したタスクを作成します。

```cpp
template<typename TResult> RTaskPtr<TResult> System::Threading::Tasks::FromException(const Exception &exception)
```

### テンプレート パラメータ

| パラメータ | 説明 |
| --- | --- |
| TResult | タスクの結果の型です。 |

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| exception | const [Exception](../../system/exception/)\& | タスクを完了させる例外です。 |

### 戻り値

指定された結果型の失敗タスクです。

## 参照

* Typedef [TaskPtr](../../system/taskptr/)
* Typedef [Exception](../../system/exception/)
* Typedef [RTaskPtr](../../system/rtaskptr/)
* 名前空間 [System::Threading::Tasks](../)
* ライブラリ [Aspose.Slides](../../)