---
title: Mutex()
second_title: Aspose.Slides for C++ API リファレンス
description: 所有されていないミューテックスを作成します。
type: docs
weight: 1
url: /ja/system.threading/mutex/mutex/
---
## Mutex::Mutex() コンストラクタ

所有されていないミューテックスを作成します。

```cpp
System::Threading::Mutex::Mutex()
```

## Mutex::Mutex(bool) コンストラクタ

コンストラクタ。

```cpp
System::Threading::Mutex::Mutex(bool initiallyOwned)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| initiallyOwned | **bool** | true の場合、構築されるミューテックスは最初に所有されます。 |

## Mutex::Mutex(bool, const String\&) コンストラクタ

コンストラクタ。

```cpp
System::Threading::Mutex::Mutex(bool initiallyOwned, const String &name)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| initiallyOwned | **bool** | true の場合、構築されるミューテックスは最初に所有されます。 |
| name | const [String](../../../system/string/)\& | ミューテックスの名前。 |

## 参照

* クラス [Mutex](../)
* クラス [String](../../../system/string/)
* 名前空間 [System::Threading](../../)
* ライブラリ [Aspose.Slides](../../../)