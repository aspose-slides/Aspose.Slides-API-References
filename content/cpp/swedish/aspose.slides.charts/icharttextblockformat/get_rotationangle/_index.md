---
title: get_RotationAngle()
second_title: Aspose.Slides för C++ API-referens
description: Anger den anpassade rotation som appliceras på texten inom den begränsande rutan. Om den inte anges används rotationen för den medföljande formen. Om den anges appliceras den oberoende av formen. Det innebär att formen kan ha en rotation applicerad utöver att texten själv har en rotation applicerad på sig. Det resulterande värdet för den visuella textrotationen sammanfattas från denna egenskap och den fördefinierade vertikala typen i egenskapen TextVerticalType. Läs float.
type: docs
weight: 235
url: /sv/aspose.slides.charts/icharttextblockformat/get_rotationangle/
---
## IChartTextBlockFormat::get_RotationAngle() metod

Anger den anpassade rotation som appliceras på texten inom den omgivande rutan. Om den inte anges används rotationen för den medföljande formen. Om den anges appliceras den oberoende av formen. Det betyder att formen kan ha en rotation applicerad utöver att texten själv har en rotation applicerad. Det resulterande värdet för den visuella textrotation sammanfattas från denna egenskap och den fördefinierade vertikala typen i egenskapen TextVerticalType. Läs **float**.

```cpp
virtual float Aspose::Slides::Charts::IChartTextBlockFormat::get_RotationAngle()=0
```

## Anmärkningar

Överväg fallet där en form har en rotation på 90 grader medurs applicerad på den. Utöver detta har textkroppen själv en rotation på -90 grader moturs applicerad på den. Då skulle den resulterande formen verka roterad men texten inom den skulle verka som om den inte hade roterats alls. 
## Se även

* Klass [IChartTextBlockFormat](../)
* Namnrymd [Aspose::Slides::Charts](../../)
* Bibliotek [Aspose.Slides](../../../)