---
title: Assert()
second_title: Aspose.Slides for C++ API リファレンス
description: 条件を検証し、失敗した場合に情報を送ります。
type: docs
weight: 14
url: /ja/system.diagnostics/debug/assert/
---
## Debug::Assert(bool) メソッド

条件を検証し、失敗した場合に情報を送ります。

```cpp
static void System::Diagnostics::Debug::Assert(bool condition)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| condition | **bool** | 条件値。 |

## Debug::Assert(bool, const String\&) メソッド

条件を検証し、失敗した場合に情報を送ります。

```cpp
static void System::Diagnostics::Debug::Assert(bool condition, const String &message)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| condition | **bool** | 条件値。 |
| message | const [String](../../../system/string/)\& | アサーション失敗時に設定するメッセージ。 |

## Debug::Assert(bool, const char *) メソッド

条件を検証し、失敗した場合に情報を送ります。

```cpp
static void System::Diagnostics::Debug::Assert(bool condition, const char *message)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| condition | **bool** | 条件値。 |
| message | const char * | アサーション失敗時に設定するメッセージ。 |

## Debug::Assert(bool, const String\&, const String\&) メソッド

条件を検証し、失敗した場合に情報を送ります。

```cpp
static void System::Diagnostics::Debug::Assert(bool condition, const String &message, const String &detailMessage)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| condition | **bool** | 条件値。 |
| message | const [String](../../../system/string/)\& | アサーション失敗時に設定するメッセージ。 |
| detailMessage | const [String](../../../system/string/)\& | アサーション失敗時に設定する詳細メッセージ。 |

## 参照

* クラス [String](../../../system/string/)
* 構造体 [Debug](../)
* 名前空間 [System::Diagnostics](../../)
* ライブラリ [Aspose.Slides](../../../)