---
title: get_RotationAngle()
second_title: Aspose.Slides för C++ API-referens
description: Anger den anpassade rotation som tillämpas på texten inom den avgränsande rutan. Om den inte är specificerad används rotationen för den medföljande formen. Om den är specificerad tillämpas den oberoende av formen. Det innebär att formen kan ha en rotation applicerad utöver att texten själv har en rotation applicerad på sig. Det resulterande värdet för visuell textrotation sammanfattas från denna egenskap och den fördefinierade vertikala typen i egenskapen TextVerticalType. Läs float.
type: docs
weight: 300
url: /sv/aspose.slides/textframeformat/get_rotationangle/
---
## TextFrameFormat::get_RotationAngle() metod

Anger den anpassade rotation som tillämpas på texten inom den avgränsande rutan. Om den inte är specificerad används rotationen för den medföljande formen. Om den är specificerad tillämpas den oberoende av formen. Det innebär att formen kan ha en rotation applicerad utöver att texten själv har en rotation applicerad på sig. Det resulterande värdet av den visuella textrotationen sammanfattas från denna egenskap och den fördefinierade vertikala typen i egenskapen TextVerticalType. Läs **float**.

```cpp
float Aspose::Slides::TextFrameFormat::get_RotationAngle() override
```

## Anmärkningar

Tänk på fallet där en form har en rotation på 90 grader medurs applicerad på den. Utöver detta har textblocket självt en rotation på -90 grader moturs applicerad på sig. Då skulle den resulterande formen verka roterad men texten inom den skulle verka som om den inte hade roterats alls.

## Se även

* Klass [TextFrameFormat](../)
* Namnrymd [Aspose::Slides](../../)
* Bibliotek [Aspose.Slides](../../../)