---
title: get_RotationAngle()
second_title: Aspose.Slides för C++ API-referens
description: Specificerar den anpassade rotation som tillämpas på texten inom begränsningsrutan. Om den inte anges används rotationen för den medföljande formen. Om den anges appliceras den oberoende av formen. Det innebär att formen kan ha en rotation utöver att texten själv har en rotation på sig. Det resulterande värdet för den visuella textrotationen sammanfattas från denna egenskap och den fördefinierade vertikala typen i egenskapen TextVerticalType. Läs float.
type: docs
weight: 339
url: /sv/aspose.slides/itextframeformat/get_rotationangle/
---
## ITextFrameFormat::get_RotationAngle() metod

Specificerar den anpassade rotation som tillämpas på texten inom begränsningsrutan. Om den inte anges används rotationen för den medföljande formen. Om den anges tillämpas den oberoende av formen. Det innebär att formen kan ha en rotation utöver att texten själv har en rotation tillämpad på sig. Det resulterande värdet för den visuella textrotation sammanfattas från denna egenskap och den fördefinierade vertikala typen i egenskapen TextVerticalType. Läs **float**.

```cpp
virtual float Aspose::Slides::ITextFrameFormat::get_RotationAngle()=0
```

## Anmärkningar

Betrakta fallet där en form har en rotation på 90 grader medurs tillämpad på den. Utöver detta har textblocket själv en rotation på -90 grader moturs tillämpad på sig. Då skulle den resulterande formen verka roterad men texten inom den skulle verka som om den inte hade roterats alls. 
## Se även

* Klass [ITextFrameFormat](../)
* Namnrymd [Aspose::Slides](../../)
* Bibliotek [Aspose.Slides](../../../)