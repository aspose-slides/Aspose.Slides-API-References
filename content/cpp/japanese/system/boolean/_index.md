---
title: Boolean
second_title: Aspose.Slides for C++ API リファレンス
description: System.Boolean .Net 型の静的メンバーを保持するクラスです。
type: docs
weight: 79
url: /ja/system/boolean/
---
## Boolean クラス

[System.Boolean](./) .[Net](../../system.net/) 型の静的メンバーを保持するクラスです。

```cpp
class Boolean
```

## メソッド

| Method | Description |
| --- | --- |
| static **bool** [Parse](./parse/)(const [String](../string/)\&) | 指定された文字列を bool 型の値に変換します。 |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, **bool**\&) | 指定された文字列を bool 型の値に変換します。 |

## フィールド

| Field | Description |
| --- | --- |
| static [FalseString](./falsestring/) | [String](../string/) は 'false' のブール値の表現です。 |
| static [TrueString](./truestring/) | [String](../string/) は 'true' のブール値の表現です。 |

## 備考



```cpp
#include <system/boolean.h>

using namespace System;

int main()
{
  // ブール変数を作成します。
  bool isWeekend = false;

  // 入力文字列を解析し、結果を出力します。
  if (Boolean::TryParse(u"True", isWeekend))
  {
    std::cout << "Is weekend: " << (isWeekend ? "Yes" : "No");
  }
  else
  {
    std::cerr << "Something went wrong" << std::endl;
  }

  return 0;
}
/*
このコード例は次の出力を生成します：
Is weekend: Yes
*/
```

## 関連項目

* 名前空間 [System](../)
* ライブラリ [Aspose.Slides](../../)