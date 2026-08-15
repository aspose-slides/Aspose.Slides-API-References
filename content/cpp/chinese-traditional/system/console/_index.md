---
title: Console
second_title: Aspose.Slides for C++ API 參考手冊
description: 提供將資料輸出至標準輸出串流的方法。這是一個沒有實例服務的靜態型別。您絕不應以任何方式建立其實例。
type: docs
weight: 196
url: /zh-hant/system/console/
---
## Console 類別


提供將資料輸出至標準輸出串流的方法。這是一個沒有實例服務的靜態型別。您絕不應以任何方式建立其實例。

```cpp
class Console
```

## 方法

| 方法 | 說明 |
| --- | --- |
| static void [Beep](./beep/)() | 未實作。 |
| static [SharedPtr](../sharedptr/)\<[System::IO::TextWriter](../../system.io/textwriter/)\>\& [get_Error](./get_error/)() | 傳回指向代表標準錯誤串流之物件的 shared pointer。 |
| static [SharedPtr](../sharedptr/)\<[System::IO::TextReader](../../system.io/textreader/)\>\& [get_In](./get_in/)() | 傳回指向代表標準輸入串流之物件的 shared pointer。 |
| static [SharedPtr](../sharedptr/)\<[System::IO::TextWriter](../../system.io/textwriter/)\>\& [get_Out](./get_out/)() | 傳回指向代表標準輸出串流之物件的 shared pointer。 |
| static void [Mute](./mute/)(**bool**) | 靜音或解除靜音標準輸出串流。 |
| static void [ReadKey](./readkey/)() | 未實作。 |
| static void [set_Title](./set_title/)(const [String](../string/)\&) | 設定主控台視窗標題。 |
| static void [SetError](./seterror/)(const [SharedPtr](../sharedptr/)\<[System::IO::TextWriter](../../system.io/textwriter/)\>\&) | 將指定的物件指派給類別的 Error 屬性。 |
| static void [SetIn](./setin/)(const [SharedPtr](../sharedptr/)\<[System::IO::TextReader](../../system.io/textreader/)\>\&) | 將 In 屬性設定為指定的 TextReader 物件。 |
| static void [SetOut](./setout/)(const [SharedPtr](../sharedptr/)\<[System::IO::TextWriter](../../system.io/textwriter/)\>\&) | 將指定的物件指派給類別的 Out 屬性。 |
| static void [Write](./write/)(const [SharedPtr](../sharedptr/)\<T\>\&) | 將指定物件的字串表示輸出至標準輸出串流。 |
| static void [Write](./write/)(**bool**) | 將 bool 值的字串表示輸出至標準輸出串流。 |
| static void [Write](./write/)(char_t) | 將指定的字元值輸出至標準輸出串流。 |
| static void [Write](./write/)(const [ArrayPtr](../arrayptr/)\<char_t\>\&) | 將指定字元陣列的字串表示輸出至標準輸出串流。 |
| static void [Write](./write/)(const [Decimal](../decimal/)\&) | 將 [Decimal](../decimal/) 值的字串表示輸出至標準輸出串流。 |
| static void [Write](./write/)(**double**) | 將 double 精度浮點數值的字串表示輸出至標準輸出串流。 |
| static void [Write](./write/)(**float**) | 將 float 精度浮點數值的字串表示輸出至標準輸出串流。 |
| static void [Write](./write/)(**int32_t**) | 將 32 位元整數值的字串表示輸出至標準輸出串流。 |
| static void [Write](./write/)(**int64_t**) | 將 64 位元整數值的字串表示輸出至標準輸出串流。 |
| static void [Write](./write/)(const [String](../string/)\&) | 將指定的字串物件輸出至標準輸出串流。 |
| static void [Write](./write/)(const char_t *) | 將指定的 C 字串輸出至標準輸出串流。 |
| static void [Write](./write/)(const [TypeInfo](../typeinfo/)\&) | 將 [TypeInfo](../typeinfo/) 值的字串表示輸出至標準輸出串流。 |
| static void [Write](./write/)(**uint32_t**) | 將無號 32 位元整數值的字串表示輸出至標準輸出串流。 |
| static void [Write](./write/)(**uint64_t**) | 將無號 64 位元整數值的字串表示輸出至標準輸出串流。 |
| static void [Write](./write/)(const [ArrayPtr](../arrayptr/)\<char_t\>\&, **int32_t**, **int32_t**) | 將指定字元陣列之指定範圍的字串表示輸出至標準輸出串流。 |
| static void [Write](./write/)(const [String](../string/)\&, Args\&&...) | 將依指定格式格式化的指定參數之字串表示輸出至標準輸出串流。 |
| static void [Write](./write/)(const char *) |  |
| static void [WriteLine](./writeline/)() | 將目前的換行字元輸出至標準輸出串流。 |
| static void [WriteLine](./writeline/)(const [SharedPtr](../sharedptr/)\<T\>\&) | 將指定物件的字串表示以及目前的換行字元一併輸出至標準輸出串流。 |
| static void [WriteLine](./writeline/)(**bool**) | 將 bool 值的字串表示以及目前的換行字元一併輸出至標準輸出串流。 |
| static void [WriteLine](./writeline/)(char_t) | 將指定的字元值以及目前的換行字元一併輸出至標準輸出串流。 |
| static void [WriteLine](./writeline/)(const [ArrayPtr](../arrayptr/)\<char_t\>\&) | 將指定字元陣列的字串表示以及目前的換行字元一併輸出至標準輸出串流。 |
| static void [WriteLine](./writeline/)(const [Decimal](../decimal/)\&) | 將 [Decimal](../decimal/) 值的字串表示以及目前的換行字元一併輸出至標準輸出串流。 |
| static void [WriteLine](./writeline/)(**double**) | 將 double 精度浮點數值的字串表示以及目前的換行字元一併輸出至標準輸出串流。 |
| static void [WriteLine](./writeline/)(**float**) | 將 float 精度浮點數值的字串表示以及目前的換行字元一併輸出至標準輸出串流。 |
| static void [WriteLine](./writeline/)(**int32_t**) | 將 32 位元整數值的字串表示以及目前的換行字元一併輸出至標準輸出串流。 |
| static void [WriteLine](./writeline/)(**int64_t**) | 將 64 位元整數值的字串表示以及目前的換行字元一併輸出至標準輸出串流。 |
| static void [WriteLine](./writeline/)(const [String](../string/)\&) | 將指定的字串物件以及目前的換行字元一併輸出至標準輸出串流。 |
| static void [WriteLine](./writeline/)(const char_t *) | 將指定的 C 字串以及目前的換行字元一併輸出至標準輸出串流。 |
| static void [WriteLine](./writeline/)(const [TypeInfo](../typeinfo/)\&) | 將 [TypeInfo](../typeinfo/) 值的字串表示以及目前的換行字元一併輸出至標準輸出串流。 |
| static void [WriteLine](./writeline/)(**uint32_t**) | 將無號 32 位元整數值的字串表示以及目前的換行字元一併輸出至標準輸出串流。 |
| static void [WriteLine](./writeline/)(**uint64_t**) | 將無號 64 位元整數值的字串表示以及目前的換行字元一併輸出至標準輸出串流。 |
| static void [WriteLine](./writeline/)(const [ArrayPtr](../arrayptr/)\<char_t\>\&, int, int) | 將指定字元陣列之指定範圍的字串表示以及目前的換行字元一併輸出至標準輸出串流。 |
| static void [WriteLine](./writeline/)(const [Exception](../exception/)\&) | 將指定的 Exception 物件的字串表示以及目前的換行字元一併輸出至標準輸出串流。 |
| static void [WriteLine](./writeline/)(const [String](../string/)\&, Args\&&...) | 將依指定格式格式化的指定參數之字串表示以及目前的換行字元一併輸出至標準輸出串流。 |
| static void [WriteLine](./writeline/)(const char *) |  |

## 備註



```cpp
#include "system/console.h"
#include <array>

int main()
{
  using namespace System;

  // 印出問候訊息。
  Console::WriteLine(u"Hello, world!");

  // 建立 'std::array' 類別的實例。
  std::array<int, 5> arr = {1, 2, 3, 4, 5};

  // 印出陣列的元素。
  for (auto el: arr)
  {
    Console::Write(u"{0} ", el);
  }
  Console::WriteLine();

  return 0;
}
/*
此程式碼範例產生以下輸出：
Hello, world!
1 2 3 4 5
*/
```

## 另見

* Namespace [System](../)
* Library [Aspose.Slides](../../)