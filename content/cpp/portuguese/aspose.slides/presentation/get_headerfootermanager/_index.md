---
title: get_HeaderFooterManager()
second_title: Aspose.Slides para C++ Referência da API
description: Retorna o gerenciador real de HeaderFooter. Somente leitura IPresentationHeaderFooterManager.
type: docs
weight: 27
url: /pt/aspose.slides/presentation/get_headerfootermanager/
---
## Presentation::get_HeaderFooterManager() método


Retorna o gerenciador real de HeaderFooter. Somente leitura [IPresentationHeaderFooterManager](../../ipresentationheaderfootermanager/).

```cpp
System::SharedPtr<IPresentationHeaderFooterManager> Aspose::Slides::Presentation::get_HeaderFooterManager() override
```

## Observações


O exemplo a seguir mostra como definir a visibilidade do rodapé dentro de [Slide](../../slide/) do PowerPoint [Presentation](../). 
```cpp
auto presentation = System::MakeObject<Presentation>(u"presentation.ppt");
auto slide = presentation->get_Slides()->idx_get(0);

System::SharedPtr<IBaseSlideHeaderFooterManager> headerFooterManager = slide->get_HeaderFooterManager();
// A propriedade IsFooterVisible é usada para indicar que um espaço reservado de rodapé de slide não está presente.
if (!headerFooterManager->get_IsFooterVisible())
{
    // O método SetFooterVisibility é usado para tornar visível um espaço reservado de rodapé de slide.
    headerFooterManager->SetFooterVisibility(true);
}

// A propriedade IsSlideNumberVisible é usada para indicar que um espaço reservado de número de página de slide não está presente.
if (!headerFooterManager->get_IsSlideNumberVisible())
{
    // O método SetSlideNumberVisibility é usado para tornar visível um espaço reservado de número de página de slide.
    headerFooterManager->SetSlideNumberVisibility(true);
}

// A propriedade IsDateTimeVisible é usada para indicar que um espaço reservado de data/hora de slide não está presente.
if (!headerFooterManager->get_IsDateTimeVisible())
{
    // O método SetFooterVisibility é usado para tornar visível um espaço reservado de data/hora de slide.
    headerFooterManager->SetDateTimeVisibility(true);
}

// O método SetFooterText é usado para definir texto no espaço reservado de rodapé de slide.
headerFooterManager->SetFooterText(u"Footer text");
// O método SetDateTimeText é usado para definir texto no espaço reservado de data/hora de slide.
headerFooterManager->SetDateTimeText(u"Date and time text");
presentation->Save(u"Presentation.ppt", SaveFormat::Ppt);
```
 O exemplo a seguir mostra como definir a visibilidade do rodapé filho dentro de [Slide](../../slide/). 
```cpp
auto presentation = System::MakeObject<Presentation>(u"presentation.ppt");
System::SharedPtr<IMasterSlideHeaderFooterManager> headerFooterManager = presentation->get_Masters()->idx_get(0)->get_HeaderFooterManager();

// O método SetFooterAndChildFootersVisibility é usado para tornar visível um slide mestre e todos os espaços reservados de rodapé filhos.
headerFooterManager->SetFooterAndChildFootersVisibility(true);

// O método SetSlideNumberAndChildSlideNumbersVisibility é usado para tornar visível um slide mestre e todos os espaços reservados de número de página filhos.
headerFooterManager->SetSlideNumberAndChildSlideNumbersVisibility(true);

// O método SetDateTimeAndChildDateTimesVisibility é usado para tornar visível um slide mestre e todos os espaços reservados de data/hora filhos.
headerFooterManager->SetDateTimeAndChildDateTimesVisibility(true);

// O método SetFooterAndChildFootersText é usado para definir texto no slide mestre e em todos os espaços reservados de rodapé filhos.
headerFooterManager->SetFooterAndChildFootersText(u"Footer text");

// O método SetDateTimeAndChildDateTimesText é usado para definir texto no slide mestre e em todos os espaços reservados de data/hora filhos.
headerFooterManager->SetDateTimeAndChildDateTimesText(u"Date and time text");
```

## Ver Também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IPresentationHeaderFooterManager](../../ipresentationheaderfootermanager/)
* Classe [Presentation](../)
* Namespace [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)