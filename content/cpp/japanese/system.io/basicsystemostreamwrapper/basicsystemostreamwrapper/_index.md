---
title: BasicSystemOStreamWrapper()
second_title: Aspose.Slides for C++ API リファレンス
description: BasicSystemOStreamWrapper の新しいインスタンスを構築します。
type: docs
weight: 1
url: /ja/system.io/basicsystemostreamwrapper/basicsystemostreamwrapper/
---
## BasicSystemOStreamWrapper::BasicSystemOStreamWrapper(SharedPtr\<Stream\>, SystemIOStreamWrappingMode) コンストラクタ


新しい [BasicSystemOStreamWrapper](../) のインスタンスを構築します。

```cpp
System::IO::BasicSystemOStreamWrapper<Elem, Traits>::BasicSystemOStreamWrapper(SharedPtr<Stream> str, SystemIOStreamWrappingMode mode=SystemIOStreamWrappingMode::Binary)
```


### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| str | [SharedPtr](../../../system/sharedptr/)\<[Stream](../../stream/)\> | ストリームへのポインタ |
| mode | [SystemIOStreamWrappingMode](../../systemiostreamwrappingmode/) | ラッピングモード |

## BasicSystemOStreamWrapper::BasicSystemOStreamWrapper(const BasicSystemOStreamWrapper\&) コンストラクタ


コピーコンストラクタ。削除されました。

```cpp
System::IO::BasicSystemOStreamWrapper<Elem, Traits>::BasicSystemOStreamWrapper(const BasicSystemOStreamWrapper &)=delete
```

## BasicSystemOStreamWrapper::BasicSystemOStreamWrapper(BasicSystemOStreamWrapper\&&) コンストラクタ


ムーブコンストラクタ。

```cpp
System::IO::BasicSystemOStreamWrapper<Elem, Traits>::BasicSystemOStreamWrapper(BasicSystemOStreamWrapper &&right) noexcept
```


### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| right | [BasicSystemOStreamWrapper](../)\&& | [Object](../../../system/object/) をムーブ |

## 参照

* 列挙体 [SystemIOStreamWrappingMode](../../systemiostreamwrappingmode/)
* 型エイリアス [SharedPtr](../../../system/sharedptr/)
* クラス [Stream](../../stream/)
* クラス [BasicSystemOStreamWrapper](../)
* 名前空間 [System::IO](../../)
* ライブラリ [Aspose.Slides](../../../)