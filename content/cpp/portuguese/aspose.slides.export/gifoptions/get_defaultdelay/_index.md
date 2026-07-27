---
title: get_DefaultDelay()
second_title: Aspose.Slides para C++ Referência da API
description: "Obtém o tempo de atraso padrão [ms]. Este valor será usado se o método ISlideShowTransition::set_AdvanceAfterTime() não for chamado. O valor padrão é 1000."
type: docs
weight: 79
url: /pt/aspose.slides.export/gifoptions/get_defaultdelay/
---
## GifOptions::get_DefaultDelay() método

Obtém o tempo de atraso padrão [ms]. Este valor será usado se o método [ISlideShowTransition::set_AdvanceAfterTime()](../../../aspose.slides/islideshowtransition/set_advanceaftertime/) não for chamado. O valor padrão é 1000.

```cpp
int32_t Aspose::Slides::Export::GifOptions::get_DefaultDelay() override
```

## Observações



```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

auto gifOptions = System::MakeObject<GifOptions>();
gifOptions->set_DefaultDelay(2000);
pres->Save(u"pres.gif", SaveFormat::Gif, gifOptions);
```

## Ver também

* Classe [GifOptions](../)
* Espaço de nomes [Aspose::Slides::Export](../../)
* Biblioteca [Aspose.Slides](../../../)