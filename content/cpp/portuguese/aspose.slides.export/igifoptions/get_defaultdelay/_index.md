---
title: get_DefaultDelay()
second_title: Aspose.Slides para Referência da API C++
description: "Obtém o tempo de atraso padrão [ms]. Este valor será usado se o método ISlideShowTransition::set_AdvanceAfterTime() não for chamado. O valor padrão é 1000."
type: docs
weight: 79
url: /pt/aspose.slides.export/igifoptions/get_defaultdelay/
---
## IGifOptions::get_DefaultDelay() método

Obtém o tempo de atraso padrão [ms]. Este valor será usado se o método [ISlideShowTransition::set_AdvanceAfterTime()](../../../aspose.slides/islideshowtransition/set_advanceaftertime/) não for chamado. O valor padrão é 1000.

```cpp
virtual int32_t Aspose::Slides::Export::IGifOptions::get_DefaultDelay()=0
```

## Observações


```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

auto gifOptions = System::MakeObject<GifOptions>();
gifOptions->set_DefaultDelay(2000);
pres->Save(u"pres.gif", SaveFormat::Gif, gifOptions);
```



## Ver Também

* Classe [IGifOptions](../)
* Espaço de nomes [Aspose::Slides::Export](../../)
* Biblioteca [Aspose.Slides](../../../)