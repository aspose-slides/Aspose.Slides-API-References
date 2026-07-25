---
title: WrapSTDIOStream()
second_title: Aspose.Slides for C++ API リファレンス
description: "std::basic_istream のようなストリームのラッパー関数です。"
type: docs
weight: 469
url: /ja/system.io/wrapstdiostream/
---
## System::IO::WrapSTDIOStream(std::basic_istream\<char_type, traits_type\>\&, STDIOStreamWrappingMode) 関数

std::basic_istream-like ストリームのラッパー関数です。

```cpp
template<typename char_type,typename traits_type> SharedPtr<Stream> System::IO::WrapSTDIOStream(std::basic_istream<char_type, traits_type> &stream, STDIOStreamWrappingMode mode=STDIOStreamWrappingMode::Binary)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| stream | std::basic_istream\<char_type, traits_type\>\& | std::basic_istream-like ストリーム |
| mode | [STDIOStreamWrappingMode](../stdiostreamwrappingmode/) | ラッピングモード |

### 戻り値

[BasicSTDIStreamWrapper](../basicstdistreamwrapper/) ラッパー

## System::IO::WrapSTDIOStream(std::basic_ostream\<char_type, traits_type\>\&, STDIOStreamWrappingMode) 関数

std::basic_ostream-like ストリームのラッパー関数です。

```cpp
template<typename char_type,typename traits_type> SharedPtr<Stream> System::IO::WrapSTDIOStream(std::basic_ostream<char_type, traits_type> &stream, STDIOStreamWrappingMode mode=STDIOStreamWrappingMode::Binary)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| stream | std::basic_ostream\<char_type, traits_type\>\& | std::basic_ostream-like ストリーム |
| mode | [STDIOStreamWrappingMode](../stdiostreamwrappingmode/) | ラッピングモード |

### 戻り値

[BasicSTDOStreamWrapper](../basicstdostreamwrapper/) ラッパー

## System::IO::WrapSTDIOStream(std::basic_iostream\<char_type, traits_type\>\&, STDIOStreamWrappingMode, STDIOStreamPositionPreference) 関数

std::basic_iostream-like ストリームのラッパー関数です。

```cpp
template<typename char_type,typename traits_type> SharedPtr<Stream> System::IO::WrapSTDIOStream(std::basic_iostream<char_type, traits_type> &stream, STDIOStreamWrappingMode mode=STDIOStreamWrappingMode::Binary, STDIOStreamPositionPreference pref_pos=STDIOStreamPositionPreference::Zero)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| stream | std::basic_iostream\<char_type, traits_type\>\& | std::basic_iostream-like ストリーム |
| mode | [STDIOStreamWrappingMode](../stdiostreamwrappingmode/) | ラッピングモード |
| pref_pos | [STDIOStreamPositionPreference](../stdiostreampositionpreference/) | 読み取り位置と書き込み位置が異なる場合に優先される位置 |

### 戻り値

[BasicSTDIOStreamWrapper](../basicstdiostreamwrapper/) ラッパー

## 参照

* 列挙体 [STDIOStreamWrappingMode](../stdiostreamwrappingmode/)
* 列挙体 [STDIOStreamPositionPreference](../stdiostreampositionpreference/)
* 型定義 [SharedPtr](../../system/sharedptr/)
* クラス [Stream](../stream/)
* 名前空間 [System::IO](../)
* ライブラリ [Aspose.Slides](../../)