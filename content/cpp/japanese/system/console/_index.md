---
title: Console
second_title: Aspose.Slides for C++ API リファレンス
description: 標準出力ストリームにデータを出力するためのメソッドを提供します。これはインスタンスサービスを持たない静的型です。いかなる手段でもインスタンスを作成してはなりません。
type: docs
weight: 196
url: /ja/system/console/
---
## Console クラス

標準出力ストリームにデータを出力するためのメソッドを提供します。これはインスタンスサービスを持たない静的型です。いかなる手段でもインスタンスを作成すべきではありません。

```cpp
class Console
```

## メソッド

| メソッド | 説明 |
| --- | --- |
| static void [Beep](./beep/)() | 実装されていません。 |
| static [SharedPtr](../sharedptr/)\<[System::IO::TextWriter](../../system.io/textwriter/)\>\& [get_Error](./get_error/)() | 標準エラーストリームを表すオブジェクトを指す共有ポインタを返します。 |
| static [SharedPtr](../sharedptr/)\<[System::IO::TextReader](../../system.io/textreader/)\>\& [get_In](./get_in/)() | 標準入力ストリームを表すオブジェクトを指す共有ポインタを返します。 |
| static [SharedPtr](../sharedptr/)\<[System::IO::TextWriter](../../system.io/textwriter/)\>\& [get_Out](./get_out/)() | 標準出力ストリームを表すオブジェクトを指す共有ポインタを返します。 |
| static void [Mute](./mute/)(**bool**) | 標準出力ストリームをミュートまたはミュート解除します。 |
| static void [ReadKey](./readkey/)() | 実装されていません。 |
| static void [set_Title](./set_title/)(const [String](../string/)\&) | コンソールウィンドウのキャプションを設定します。 |
| static void [SetError](./seterror/)(const [SharedPtr](../sharedptr/)\<[System::IO::TextWriter](../../system.io/textwriter/)\>\&) | 指定されたオブジェクトをクラスの Error プロパティに割り当てます。 |
| static void [SetIn](./setin/)(const [SharedPtr](../sharedptr/)\<[System::IO::TextReader](../../system.io/textreader/)\>\&) | In プロパティを指定された TextReader オブジェクトに設定します。 |
| static void [SetOut](./setout/)(const [SharedPtr](../sharedptr/)\<[System::IO::TextWriter](../../system.io/textwriter/)\>\&) | 指定されたオブジェクトをクラスの Out プロパティに割り当てます。 |
| static void [Write](./write/)(const [SharedPtr](../sharedptr/)\<T\>\&) | 指定されたオブジェクトの文字列表現を標準出力ストリームに出力します。 |
| static void [Write](./write/)(**bool**) | bool 値の文字列表現を標準出力ストリームに出力します。 |
| static void [Write](./write/)(char_t) | 指定された文字値を標準出力ストリームに出力します。 |
| static void [Write](./write/)(const [ArrayPtr](../arrayptr/)\<char_t\>\&) | 指定された文字配列の文字列表現を標準出力ストリームに出力します。 |
| static void [Write](./write/)(const [Decimal](../decimal/)\&) | [Decimal](../decimal/) の文字列表現を標準出力ストリームに出力します。 |
| static void [Write](./write/)(**double**) | double 精度浮動小数点値の文字列表現を標準出力ストリームに出力します。 |
| static void [Write](./write/)(**float**) | float 精度浮動小数点値の文字列表現を標準出力ストリームに出力します。 |
| static void [Write](./write/)(**int32_t**) | 32 ビット整数値の文字列表現を標準出力ストリームに出力します。 |
| static void [Write](./write/)(**int64_t**) | 64 ビット整数値の文字列表現を標準出力ストリームに出力します。 |
| static void [Write](./write/)(const [String](../string/)\&) | 指定された文字列オブジェクトを標準出力ストリームに出力します。 |
| static void [Write](./write/)(const char_t *) | 指定された C 文字列を標準出力ストリームに出力します。 |
| static void [Write](./write/)(const [TypeInfo](../typeinfo/)\&) | [TypeInfo](../typeinfo/) の文字列表現を標準出力ストリームに出力します。 |
| static void [Write](./write/)(**uint32_t**) | 符号なし 32 ビット整数値の文字列表現を標準出力ストリームに出力します。 |
| static void [Write](./write/)(**uint64_t**) | 符号なし 64 ビット整数値の文字列表現を標準出力ストリームに出力します。 |
| static void [Write](./write/)(const [ArrayPtr](../arrayptr/)\<char_t\>\&, **int32_t**, **int32_t**) | 指定された文字配列の指定された範囲の文字列表現を標準出力ストリームに出力します。 |
| static void [Write](./write/)(const [String](../string/)\&, Args\&&...) | 指定されたフォーマットに従ってフォーマットされた指定引数の文字列表現を標準出力ストリームに出力します。 |
| static void [Write](./write/)(const char *) |  |
| static void [WriteLine](./writeline/)() | 現在の行終端子を標準出力ストリームに出力します。 |
| static void [WriteLine](./writeline/)(const [SharedPtr](../sharedptr/)\<T\>\&) | 指定されたオブジェクトの文字列表現を現在の行終端子と共に標準出力ストリームに出力します。 |
| static void [WriteLine](./writeline/)(**bool**) | bool 値の文字列表現を現在の行終端子と共に標準出力ストリームに出力します。 |
| static void [WriteLine](./writeline/)(char_t) | 指定された文字値を現在の行終端子と共に標準出力ストリームに出力します。 |
| static void [WriteLine](./writeline/)(const [ArrayPtr](../arrayptr/)\<char_t\>\&) | 指定された文字配列の文字列表現を現在の行終端子と共に標準出力ストリームに出力します。 |
| static void [WriteLine](./writeline/)(const [Decimal](../decimal/)\&) | [Decimal](../decimal/) の文字列表現を現在の行終端子と共に標準出力ストリームに出力します。 |
| static void [WriteLine](./writeline/)(**double**) | double 精度浮動小数点値の文字列表現を現在の行終端子と共に標準出力ストリームに出力します。 |
| static void [WriteLine](./writeline/)(**float**) | float 精度浮動小数点値の文字列表現を現在の行終端子と共に標準出力ストリームに出力します。 |
| static void [WriteLine](./writeline/)(**int32_t**) | 32 ビット整数値の文字列表現を現在の行終端子と共に標準出力ストリームに出力します。 |
| static void [WriteLine](./writeline/)(**int64_t**) | 64 ビット整数値の文字列表現を現在の行終端子と共に標準出力ストリームに出力します。 |
| static void [WriteLine](./writeline/)(const [String](../string/)\&) | 指定された文字列オブジェクトを現在の行終端子と共に標準出力ストリームに出力します。 |
| static void [WriteLine](./writeline/)(const char_t *) | 指定された C 文字列を現在の行終端子と共に標準出力ストリームに出力します。 |
| static void [WriteLine](./writeline/)(const [TypeInfo](../typeinfo/)\&) | [TypeInfo](../typeinfo/) の文字列表現を現在の行終端子と共に標準出力ストリームに出力します。 |
| static void [WriteLine](./writeline/)(**uint32_t**) | 符号なし 32 ビット整数値の文字列表現を現在の行終端子と共に標準出力ストリームに出力します。 |
| static void [WriteLine](./writeline/)(**uint64_t**) | 符号なし 64 ビット整数値の文字列表現を現在の行終端子と共に標準出力ストリームに出力します。 |
| static void [WriteLine](./writeline/)(const [ArrayPtr](../arrayptr/)\<char_t\>\&, int, int) | 指定された文字配列の指定された範囲の文字列表現を現在の行終端子と共に標準出力ストリームに出力します。 |
| static void [WriteLine](./writeline/)(const [Exception](../exception/)\&) | 指定された Exception オブジェクトの文字列表現を現在の行終端子と共に標準出力ストリームに出力します。 |
| static void [WriteLine](./writeline/)(const [String](../string/)\&, Args\&&...) | 指定されたフォーマットに従ってフォーマットされた指定引数の文字列表現を現在の行終端子と共に標準出力ストリームに出力します。 |
| static void [WriteLine](./writeline/)(const char *) |  |

## 備考

```cpp
#include "system/console.h"
#include <array>

int main()
{
  using namespace System;

  // Hello メッセージを出力します。
  Console::WriteLine(u"Hello, world!");

  // 'std::array' クラスのインスタンスを作成します。
  std::array<int, 5> arr = {1, 2, 3, 4, 5};

  // 配列の要素を出力します。
  for (auto el: arr)
  {
    Console::Write(u"{0} ", el);
  }
  Console::WriteLine();

  return 0;
}
/*
このコード例は次の出力を生成します:
Hello, world!
1 2 3 4 5
*/
```

## 参照

* 名前空間 [System](../)
* ライブラリ [Aspose.Slides](../../)