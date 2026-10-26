---
title: BasicSystemIStreamWrapper()
second_title: Aspose.Slides for C++ API リファレンス
description: BasicSystemIStreamWrapper の新しいインスタンスを構築します。
type: docs
weight: 1
url: /ja/system.io/basicsystemistreamwrapper/basicsystemistreamwrapper/
---
## BasicSystemIStreamWrapper::BasicSystemIStreamWrapper(SharedPtr\<Stream\>, SystemIOStreamWrappingMode) コンストラクター

[BasicSystemIStreamWrapper](../) の新しいインスタンスを構築します。

```cpp
System::IO::BasicSystemIStreamWrapper<Elem, Traits>::BasicSystemIStreamWrapper(SharedPtr<Stream> str, SystemIOStreamWrappingMode mode=SystemIOStreamWrappingMode::Binary)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| str | [SharedPtr](../../../system/sharedptr/)\<[Stream](../../stream/)\> | ストリームへのポインタ |
| mode | [SystemIOStreamWrappingMode](../../systemiostreamwrappingmode/) | ラッピングモード |

## BasicSystemIStreamWrapper::BasicSystemIStreamWrapper(const BasicSystemIStreamWrapper\&) コンストラクター

コピーコンストラクタ。削除されています。

```cpp
System::IO::BasicSystemIStreamWrapper<Elem, Traits>::BasicSystemIStreamWrapper(const BasicSystemIStreamWrapper &)=delete
```

## BasicSystemIStreamWrapper::BasicSystemIStreamWrapper(BasicSystemIStreamWrapper\&&) コンストラクター

ムーブコンストラクタ。

```cpp
System::IO::BasicSystemIStreamWrapper<Elem, Traits>::BasicSystemIStreamWrapper(BasicSystemIStreamWrapper &&right) noexcept
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| right | [BasicSystemIStreamWrapper](../)\&& | [Object](../../../system/object/) のムーブ対象 |

## 参照

* 列挙型 [SystemIOStreamWrappingMode](../../systemiostreamwrappingmode/)
* 型定義 [SharedPtr](../../../system/sharedptr/)
* クラス [Stream](../../stream/)
* クラス [BasicSystemIStreamWrapper](../)
* 名前空間 [System::IO](../../)
* ライブラリ [Aspose.Slides](../../../)