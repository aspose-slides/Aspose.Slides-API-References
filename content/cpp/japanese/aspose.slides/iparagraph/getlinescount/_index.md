---
title: GetLinesCount()
second_title: Aspose.Slides for C++ API リファレンス
description: 段落内の行数を取得します。
type: docs
weight: 105
url: /ja/aspose.slides/iparagraph/getlinescount/
---
## IParagraph::GetLinesCount() メソッド


段落内の行数を取得します。

```cpp
virtual int32_t Aspose::Slides::IParagraph::GetLinesCount()=0
```


### 戻り値

段落内の行数
## 備考


例: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<ISlide> sld = pres->get_Slide(0);
System::SharedPtr<IAutoShape> ashp = sld->get_Shapes()->AddAutoShape(ShapeType::Rectangle, 150.0f, 75.0f, 150.0f, 50.0f);
System::SharedPtr<IParagraph> para = ashp->get_TextFrame()->get_Paragraph(0);
System::SharedPtr<IPortion> portion = para->get_Portion(0);
portion->set_Text(u"Aspose Paragraph GetLinesCount() Example");
System::Console::WriteLine(u"Lines Count = {0}", para->GetLinesCount());
```


## 参照

* クラス [IParagraph](../)
* 名前空間 [Aspose::Slides](../../)
* ライブラリ [Aspose.Slides](../../../)