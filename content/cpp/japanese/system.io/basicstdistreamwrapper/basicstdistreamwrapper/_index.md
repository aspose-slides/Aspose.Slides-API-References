---
title: BasicSTDIStreamWrapper()
second_title: Aspose.Slides for C++ API リファレンス
description: BasicSTDIStreamWrapper の新しいインスタンスを構築します。
type: docs
weight: 14
url: /ja/system.io/basicstdistreamwrapper/basicstdistreamwrapper/
---
## BasicSTDIStreamWrapper::BasicSTDIStreamWrapper(std::basic_istream\<char_type, traits_type\>\&, STDIOStreamWrappingMode) コンストラクタ

[BasicSTDIStreamWrapper](../) の新しいインスタンスを構築します。

```cpp
System::IO::BasicSTDIStreamWrapper<T, typename>::BasicSTDIStreamWrapper(std::basic_istream<char_type, traits_type> &str, STDIOStreamWrappingMode mode=STDIOStreamWrappingMode::Binary)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| str | std::basic_istream\<[char_type](../../stdiostreamwrapperbase/char_type/), [traits_type](../../stdiostreamwrapperbase/traits_type/)\>\& | ストリームへの参照 |
| mode | [STDIOStreamWrappingMode](../../stdiostreamwrappingmode/) | ラッピングモード |

## BasicSTDIStreamWrapper::BasicSTDIStreamWrapper(const BasicSTDIStreamWrapper\&) コンストラクタ

コピーコンストラクタ。削除されました。

```cpp
System::IO::BasicSTDIStreamWrapper<T, typename>::BasicSTDIStreamWrapper(const BasicSTDIStreamWrapper &)=delete
```

## 参照

* 列挙型 [STDIOStreamWrappingMode](../../stdiostreamwrappingmode/)
* 型定義 [char_type](../../stdiostreamwrapperbase/char_type/)
* 型定義 [traits_type](../../stdiostreamwrapperbase/traits_type/)
* クラス [BasicSTDIStreamWrapper](../)
* 名前空間 [System::IO](../../)
* ライブラリ [Aspose.Slides](../../../)