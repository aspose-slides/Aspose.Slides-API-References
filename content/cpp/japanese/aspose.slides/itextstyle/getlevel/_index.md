---
title: GetLevel()
second_title: Aspose.Slides C++ 用 API リファレンス
description: スタイルのレベルが存在すればそれを返し、存在しなければ null を返します。
type: docs
weight: 14
url: /ja/aspose.slides/itextstyle/getlevel/
---
## ITextStyle::GetLevel(int32_t) メソッド


スタイルのレベルが存在すればそれを返し、存在しない場合は null を返します。

```cpp
virtual System::SharedPtr<IParagraphFormat> Aspose::Slides::ITextStyle::GetLevel(int32_t index)=0
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| index | **int32_t** | レベルのゼロベースインデックス。0..8 の範囲で指定する必要があります。 |

### 戻り値

レベル [IParagraphFormat](../../iparagraphformat/) の書式設定。

## 参照

* 型定義 [SharedPtr](../../../system/sharedptr/)
* クラス [IParagraphFormat](../../iparagraphformat/)
* クラス [ITextStyle](../)
* 名前空間 [Aspose::Slides](../../)
* ライブラリ [Aspose.Slides](../../../)