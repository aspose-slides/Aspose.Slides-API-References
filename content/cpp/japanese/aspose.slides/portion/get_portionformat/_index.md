---
title: get_PortionFormat()
second_title: Aspose.Slides の C++ API リファレンス
description: 継承が適用されていないテキスト部分の明示的に設定された書式プロパティを含む書式オブジェクトを返します。 読み取り専用 IPortionFormat.
type: docs
weight: 1
url: /ja/aspose.slides/portion/get_portionformat/
---
## Portion::get_PortionFormat() メソッド

継承が適用されていないテキスト部分の明示的に設定された書式プロパティを含む書式オブジェクトを返します。 読み取り専用 [IPortionFormat](../../iportionformat/).

```cpp
System::SharedPtr<IPortionFormat> Aspose::Slides::Portion::get_PortionFormat() override
```

## 備考

書式オブジェクトは現在の部分に対して定義された書式パラメータのみを含み、継承されたデータは適用されません。

継承された値を含む実効値を取得するには、[PortionFormat::GetEffective](../../portionformat/geteffective/) メソッドを使用します。

## 参照

* Typedef [SharedPtr](../../../system/sharedptr/)
* クラス [IPortionFormat](../../iportionformat/)
* クラス [Portion](../)
* 名前空間 [Aspose::Slides](../../)
* ライブラリ [Aspose.Slides](../../../)