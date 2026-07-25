---
title: set_OperatorEmulator()
second_title: Aspose.Slides for C++ API リファレンス
description: "オペレータエミュレータ。true の場合、ボックスとその内容は単一のオペレータとして動作し、オペレータのプロパティを継承します。つまり、例えば文字が改行ポイントとして機能し、他のオペレータに揃えることができる、ということです。オペレータエミュレータは、'==' のように 1 つ以上の字形が結合してオペレータを形成する場合に頻繁に使用されます。デフォルト値: false"
type: docs
weight: 27
url: /ja/aspose.slides.mathtext/imathbox/set_operatoremulator/
---
## IMathBox::set_OperatorEmulator(bool) method


オペレータエミュレータ。true の場合、ボックスとその内容は単一のオペレータとして動作し、オペレータのプロパティを継承します。つまり、例えば文字が改行ポイントとして機能し、他のオペレータに揃えることができる、ということです。オペレータエミュレータは、'==' のように 1 つ以上の字形が結合してオペレータを形成する場合に頻繁に使用されます。デフォルト値: false

```cpp
virtual void Aspose::Slides::MathText::IMathBox::set_OperatorEmulator(bool value)=0
```

## Remarks


例: 
```cpp
auto box = System::MakeObject<MathematicalText>(u"==")->ToBox();
box->set_OperatorEmulator(true);
```

## See Also

* Class [IMathBox](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)