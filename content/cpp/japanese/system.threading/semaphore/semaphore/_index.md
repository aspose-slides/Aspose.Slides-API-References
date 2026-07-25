---
title: Semaphore()
second_title: Aspose.Slides for C++ APIリファレンス
description: 名前なしセマフォを作成します。
type: docs
weight: 1
url: /ja/system.threading/semaphore/semaphore/
---
## Semaphore::Semaphore(int, int) コンストラクタ

名前なしセマフォを作成します。

```cpp
System::Threading::Semaphore::Semaphore(int initialCount, int maximumCount)
```

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| initialCount | int | アクティブエントリの初期カウント。 |
| maximumCount | int | 許容されるエントリの最大数。 |

## Semaphore::Semaphore(int, int, const String\&) コンストラクタ

名前付きセマフォを作成します。

```cpp
System::Threading::Semaphore::Semaphore(int initialCount, int maximumCount, const String &name)
```

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| initialCount | int | アクティブエントリの初期カウント。 |
| maximumCount | int | 許容されるエントリの最大数。 |
| name | const [String](../../../system/string/)\& | [Semaphore](../) 名。 |

## Semaphore::Semaphore(int, int, const String\&, bool\&) コンストラクタ

名前付きセマフォを作成します。

```cpp
System::Threading::Semaphore::Semaphore(int initialCount, int maximumCount, const String &name, bool &createdNew)
```

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| initialCount | int | アクティブエントリの初期カウント。 |
| maximumCount | int | 許容されるエントリの最大数。 |
| name | const [String](../../../system/string/)\& | [Semaphore](../) 名。 |
| createdNew | **bool**\& | セマフォが作成された場合は true に、同名の既存セマフォが再利用された場合は false に設定される変数への参照 |

## 参照

* クラス [Semaphore](../)
* クラス [String](../../../system/string/)
* 名前空間 [System::Threading](../../)
* ライブラリ [Aspose.Slides](../../../)