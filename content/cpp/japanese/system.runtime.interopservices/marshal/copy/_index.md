---
title: Copy()
second_title: Aspose.Slides for C++ API リファレンス
description: public static void Copy(IntPtr source, byte[] destination, int startIndex, int length) のセマンティクスを実装します。
type: docs
weight: 1
url: /ja/system.runtime.interopservices/marshal/copy/
---
## Marshal::Copy(const IntPtr, container\&&, int, int) メソッド

public static void Copy(IntPtr source, byte[] destination, int startIndex, int length) のセマンティクスを実装します。

```cpp
template<typename container> static void System::Runtime::InteropServices::Marshal::Copy(const IntPtr source, container &&destination, int startIndex, int length)
```

### テンプレート パラメータ

| パラメータ | 説明 |
| --- | --- |
| container | 宛先コンテナの型。 |

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| source | const IntPtr | ソースデータポインタ。 |
| destination | container\&& | データをコピーするコンテナ。 |
| startIndex | int | ソースの開始インデックス。 |
| length | int | コピーする要素数。 |

## Marshal::Copy(const void *, container\&&, int, int) メソッド

public static void Copy(IntPtr source, byte[] destination, int startIndex, int length) のセマンティクスを実装します。

```cpp
template<typename container> static void System::Runtime::InteropServices::Marshal::Copy(const void *source, container &&destination, int startIndex, int length)
```

### テンプレート パラメータ

| パラメータ | 説明 |
| --- | --- |
| container | 宛先コンテナの型。 |

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| source | const void * | ソースデータポインタ。 |
| destination | container\&& | データをコピーするコンテナ。 |
| startIndex | int | ソースの開始インデックス。 |
| length | int | コピーする要素数。 |

## Marshal::Copy(const container\&, int, void *, int) メソッド

public static void Copy(char[] source, int startIndex, IntPtr destination, int length) を実装します。

```cpp
template<typename container> static void System::Runtime::InteropServices::Marshal::Copy(const container &source, int startIndex, void *destination, int length)
```

### テンプレート パラメータ

| パラメータ | 説明 |
| --- | --- |
| container | ソースコンテナの型。 |

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| source | const container\& | ソースデータポインタ。 |
| startIndex | int | ソースの開始インデックス。 |
| destination | void * | 宛先データポインタ。 |
| length | int | コピーする要素数。 |

## Marshal::Copy(const container\&, int, IntPtr, int) メソッド

public static void Copy(char[] source, int startIndex, IntPtr destination, int length) を実装します。

```cpp
template<typename container> static void System::Runtime::InteropServices::Marshal::Copy(const container &source, int startIndex, IntPtr destination, int length)
```

### テンプレート パラメータ

| パラメータ | 説明 |
| --- | --- |
| container | ソースコンテナの型。 |

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| source | const container\& | ソースデータポインタ。 |
| startIndex | int | ソースの開始インデックス。 |
| destination | IntPtr | 宛先データポインタ。 |
| length | int | コピーする要素数。 |

## 参照

* クラス [Marshal](../)
* 名前空間 [System::Runtime::InteropServices](../../)
* ライブラリ [Aspose.Slides](../../../)