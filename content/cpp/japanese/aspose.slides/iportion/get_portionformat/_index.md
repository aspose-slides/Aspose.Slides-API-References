---
title: get_PortionFormat()
second_title: Aspose.Slides for C++ API リファレンス
description: 継承が適用されていないテキスト部分の、明示的に設定された書式プロパティを含む書式オブジェクトを返します。読み取り専用 IPortionFormat.
type: docs
weight: 1
url: /ja/aspose.slides/iportion/get_portionformat/
---
## IPortion::get_PortionFormat() メソッド

継承が適用されていないテキスト部分の、明示的に設定された書式プロパティを含む書式オブジェクトを返します。読み取り専用 [IPortionFormat](../../iportionformat/)。

```cpp
virtual System::SharedPtr<IPortionFormat> Aspose::Slides::IPortion::get_PortionFormat()=0
```

## 備考

この書式オブジェクトは、現在の部分に対して定義された書式パラメータのみを含み、継承されたデータは適用されません。

継承された値を含む有効な値を取得するには、[IPortionFormat::GetEffective](../../iportionformat/geteffective/) メソッドを使用します。

## 参照

* Typedef [SharedPtr](../../../system/sharedptr/)
* クラス [IPortionFormat](../../iportionformat/)
* クラス [IPortion](../)
* 名前空間 [Aspose::Slides](../../)
* ライブラリ [Aspose.Slides](../../../)