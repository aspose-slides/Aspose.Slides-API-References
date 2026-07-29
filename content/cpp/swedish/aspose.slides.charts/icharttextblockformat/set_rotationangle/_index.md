---
title: set_RotationAngle()
second_title: Aspose.Slides för C++ API-referens
description: Anger den anpassade rotation som tillämpas på texten inom begränsningsrutan. Om den inte anges används rotationen för den medföljande formen. Om den anges appliceras den oberoende av formen. Det innebär att formen kan ha en rotation utöver att texten själv har en rotation applicerad på den. Det resulterande värdet för den visuella textrotationen summeras från denna egenskap och den fördefinierade vertikala typen i egenskapen TextVerticalType. Skriv float.
type: docs
weight: 248
url: /sv/aspose.slides.charts/icharttextblockformat/set_rotationangle/
---
## IChartTextBlockFormat::set_RotationAngle(float) metod

Anger den anpassade rotation som tillämpas på texten inom begränsningsrutan. Om den inte anges används rotationen för den medföljande formen. Om den anges appliceras den oberoende av formen. Det innebär att formen kan ha en rotation utöver att texten själv har en rotation applicerad på den. Det resulterande värdet för den visuella textrotationen summeras från denna egenskap och den fördefinierade vertikala typen i egenskapen TextVerticalType. Skriv **float**.

```cpp
virtual void Aspose::Slides::Charts::IChartTextBlockFormat::set_RotationAngle(float value)=0
```

## Anmärkningar

Överväg fallet där en form har en rotation på 90 grader medurs applicerad på den. Utöver detta har textkroppen själv en rotation på -90 grader moturs applicerad på den. Då skulle den resulterande formen framstå som roterad men texten inom den skulle framstå som om den inte hade roterats alls.

## Se även

* Klass [IChartTextBlockFormat](../)
* Namnrymd [Aspose::Slides::Charts](../../)
* Bibliotek [Aspose.Slides](../../../)