---
title: BasicSTDOStreamWrapper()
second_title: Aspose.Slides for C++ API リファレンス
description: BasicSTDOStreamWrapper の新しいインスタンスを作成します。
type: docs
weight: 14
url: /ja/system.io/basicstdostreamwrapper/basicstdostreamwrapper/
---
## BasicSTDOStreamWrapper::BasicSTDOStreamWrapper(std::basic_ostream\<char_type, traits_type\>\&, STDIOStreamWrappingMode) コンストラクタ

[BasicSTDOStreamWrapper](../) の新しいインスタンスを作成します。

```cpp
System::IO::BasicSTDOStreamWrapper<T, typename>::BasicSTDOStreamWrapper(std::basic_ostream<char_type, traits_type> &str, STDIOStreamWrappingMode mode=STDIOStreamWrappingMode::Binary)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| str | std::basic_ostream\<[char_type](../../stdiostreamwrapperbase/char_type/), [traits_type](../../stdiostreamwrapperbase/traits_type/)\>\& | ストリームへの参照 |
| mode | [STDIOStreamWrappingMode](../../stdiostreamwrappingmode/) | ラッピングモード |

## BasicSTDOStreamWrapper::BasicSTDOStreamWrapper(const BasicSTDOStreamWrapper\&) コンストラクタ

コピーコンストラクタ。削除されました。

```cpp
System::IO::BasicSTDOStreamWrapper<T, typename>::BasicSTDOStreamWrapper(const BasicSTDOStreamWrapper &)=delete
```

## 参照

* 列挙型 [STDIOStreamWrappingMode](../../stdiostreamwrappingmode/)
* 型定義 [char_type](../../stdiostreamwrapperbase/char_type/)
* 型定義 [traits_type](../../stdiostreamwrapperbase/traits_type/)
* クラス [BasicSTDOStreamWrapper](../)
* 名前空間 [System::IO](../../)
* ライブラリ [Aspose.Slides](../../../)