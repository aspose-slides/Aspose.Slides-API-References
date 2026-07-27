---
title: WriteAsEmf()
second_title: Referência da API Aspose.Slides para C++
description: Salva o conteúdo do slide como um arquivo EMF.
type: docs
weight: 170
url: /pt/aspose.slides/slide/writeasemf/
---
## Slide::WriteAsEmf(System::SharedPtr\<System::IO::Stream\>) método

Salva o conteúdo do slide como um arquivo EMF.

```cpp
void Aspose::Slides::Slide::WriteAsEmf(System::SharedPtr<System::IO::Stream> stream) override
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Stream de destino |
## Observações

O exemplo de código a seguir demonstra como converter o primeiro slide de uma apresentação PowerPoint em um metafile.
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<System::IO::Stream> fileStream = System::IO::File::Create(u"slide_1.emf");

// Salva o primeiro slide como um metafile
pres->get_Slide(0)->WriteAsEmf(fileStream);
```

## Veja Também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [Stream](../../../system.io/stream/)
* Classe [Slide](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)