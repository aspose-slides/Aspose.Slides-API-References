---
title: GetLevel()
second_title: Aspose.Slides の C++ API リファレンス
description: スタイルのレベルが存在すればそれを返し、存在しなければ null を返します。
type: docs
weight: 14
url: /ja/aspose.slides/textstyle/getlevel/
---
## TextStyle::GetLevel(int32_t) メソッド

スタイルのレベルが存在する場合はそれを返し、存在しない場合は null を返します。

```cpp
System::SharedPtr<IParagraphFormat> Aspose::Slides::TextStyle::GetLevel(int32_t index) override
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| index | **int32_t** | レベルのゼロベースインデックス。0..8 の範囲内である必要があります。 |

### 戻り値

レベル [IParagraphFormat](../../iparagraphformat/) の書式設定。

## 参照

* 型定義 [SharedPtr](../../../system/sharedptr/)
* クラス [IParagraphFormat](../../iparagraphformat/)
* クラス [TextStyle](../)
* 名前空間 [Aspose::Slides](../../)
* ライブラリ [Aspose.Slides](../../../)