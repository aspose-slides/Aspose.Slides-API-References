---
title: BasicSTDIOStreamWrapper()
second_title: Aspose.Slides for C++ API リファレンス
description: BasicSTDIOStreamWrapper の新しいインスタンスを構築します。
type: docs
weight: 14
url: /ja/system.io/basicstdiostreamwrapper/basicstdiostreamwrapper/
---
## BasicSTDIOStreamWrapper::BasicSTDIOStreamWrapper(std::basic_iostream\<char_type, traits_type\>\&, STDIOStreamWrappingMode, STDIOStreamPositionPreference) コンストラクタ

[BasicSTDIOStreamWrapper](../) の新しいインスタンスを構築します。

```cpp
System::IO::BasicSTDIOStreamWrapper<T, typename>::BasicSTDIOStreamWrapper(std::basic_iostream<char_type, traits_type> &str, STDIOStreamWrappingMode mode=STDIOStreamWrappingMode::Binary, STDIOStreamPositionPreference pref_pos=STDIOStreamPositionPreference::Zero)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| str | std::basic_iostream\<[char_type](../../stdiostreamwrapperbase/char_type/), [traits_type](../../stdiostreamwrapperbase/traits_type/)\>\& | ストリームへの参照 |
| mode | [STDIOStreamWrappingMode](../../stdiostreamwrappingmode/) | ラッピングモード |
| pref_pos | [STDIOStreamPositionPreference](../../stdiostreampositionpreference/) | 読み取り位置と書き込み位置が異なる場合に、読み取り位置および書き込み位置として好まれる位置 |

## BasicSTDIOStreamWrapper::BasicSTDIOStreamWrapper(const BasicSTDIOStreamWrapper\&) コンストラクタ

コピーコンストラクタ。削除されました。

```cpp
System::IO::BasicSTDIOStreamWrapper<T, typename>::BasicSTDIOStreamWrapper(const BasicSTDIOStreamWrapper &)=delete
```

## 参照

* 列挙型 [STDIOStreamWrappingMode](../../stdiostreamwrappingmode/)
* 列挙型 [STDIOStreamPositionPreference](../../stdiostreampositionpreference/)
* 型定義 [char_type](../../stdiostreamwrapperbase/char_type/)
* 型定義 [traits_type](../../stdiostreamwrapperbase/traits_type/)
* クラス [BasicSTDIOStreamWrapper](../)
* 名前空間 [System::IO](../../)
* ライブラリ [Aspose.Slides](../../../)