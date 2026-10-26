---
title: set_RotationAngle()
second_title: Aspose.Slides för C++ API-referens
description: Anger den anpassade rotation som tillämpas på texten inom begränsningsrutan. Om den inte anges används rotationen för den medföljande formen. Om den anges tillämpas den oberoende av formen. Det betyder att formen kan ha en rotation utöver att själva texten har en rotation applicerad på sig. Det resulterande värdet för visuell textrotation sammanfattas från denna egenskap och den fördefinierade vertikala typen i egenskapen TextVerticalType. Skriv float.
type: docs
weight: 313
url: /sv/aspose.slides/textframeformat/set_rotationangle/
---
## TextFrameFormat::set_RotationAngle(float) metod

Anger den anpassade rotation som tillämpas på texten inom begränsningsrutan. Om den inte anges används rotationen för den medföljande formen. Om den anges tillämpas den oberoende av formen. Det betyder att formen kan ha en rotation utöver att själva texten har en rotation applicerad på sig. Det resulterande värdet för visuell textrotation sammanfattas från denna egenskap och den fördefinierade vertikala typen i egenskapen TextVerticalType. Skriv **float**.

```cpp
void Aspose::Slides::TextFrameFormat::set_RotationAngle(float value) override
```

## Anmärkningar

Fundera på fallet där en form har en rotation på 90 grader medurs applicerad på den. Utöver detta har själva textkroppen en rotation på -90 grader moturs applicerad på sig. Då skulle den resulterande formen verka roterad men texten inom den verka som om den inte hade roterats alls. 
## Se också

* Klass [TextFrameFormat](../)
* Namnrymd [Aspose::Slides](../../)
* Bibliotek [Aspose.Slides](../../../)