---
title: set_RotationAngle()
second_title: Aspose.Slides för C++ API-referens
description: Anger den anpassade rotationen som appliceras på texten inom begränsningsrutan. Om den inte specificeras används rotationen för den medföljande formen. Om den specificeras tillämpas den oberoende av formen. Det innebär att formen kan ha en rotation applicerad utöver att själva texten har en rotation applicerad på sig. Det resulterande värdet för den visuella textrotationen summeras från denna egenskap och den fördefinierade vertikala typen i egenskapen TextVerticalType. Skriv float.
type: docs
weight: 352
url: /sv/aspose.slides/itextframeformat/set_rotationangle/
---
## ITextFrameFormat::set_RotationAngle(float) metod


Anger den anpassade rotationen som appliceras på texten inom begränsningsrutan. Om den inte specificeras används rotationen för den medföljande formen. Om den specificeras tillämpas den oberoende av formen. Det innebär att formen kan ha en rotation applicerad utöver att själva texten har en rotation applicerad på sig. Det resulterande värdet för den visuella textrotation som summeras från denna egenskap och den fördefinierade vertikala typen i egenskapen TextVerticalType. Skriv **float**.

```cpp
virtual void Aspose::Slides::ITextFrameFormat::set_RotationAngle(float value)=0
```

## Anmärkningar


Tänk på fallet där en form har en rotation på 90 grader medurs applicerad på den. Utöver detta har textblocket själv en rotation på -90 grader moturs applicerad på sig. Då skulle den resulterande formen verka roterad men texten inom den skulle verka som om den inte hade roterats alls.

## Se även

* Klass [ITextFrameFormat](../)
* Namnrymd [Aspose::Slides](../../)
* Bibliotek [Aspose.Slides](../../../)