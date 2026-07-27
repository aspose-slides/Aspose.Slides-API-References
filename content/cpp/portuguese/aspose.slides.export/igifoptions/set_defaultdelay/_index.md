---
title: set_DefaultDelay()
second_title: Referência da API Aspose.Slides para C++
description: "Define o tempo de atraso padrão [ms]. Este valor será usado se o método ISlideShowTransition::set_AdvanceAfterTime() não for chamado. O valor padrão é 1000."
type: docs
weight: 92
url: /pt/aspose.slides.export/igifoptions/set_defaultdelay/
---
## IGifOptions::set_DefaultDelay(int32_t) método


Define o tempo de atraso padrão [ms]. Este valor será usado se o método [ISlideShowTransition::set_AdvanceAfterTime()](../../../aspose.slides/islideshowtransition/set_advanceaftertime/) não for chamado. O valor padrão é 1000.

```cpp
virtual void Aspose::Slides::Export::IGifOptions::set_DefaultDelay(int32_t value)=0
```

## Observações



```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

auto gifOptions = System::MakeObject<GifOptions>();
gifOptions->set_DefaultDelay(2000);
pres->Save(u"pres.gif", SaveFormat::Gif, gifOptions);
```




## Veja também

* classe [IGifOptions](../)
* espaço de nomes [Aspose::Slides::Export](../../)
* Biblioteca [Aspose.Slides](../../../)