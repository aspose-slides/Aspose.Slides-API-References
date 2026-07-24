---
title: SplitTextByColumns()
second_title: Aspose.Slides for C++ API Referansı
description: ITextFrame öğesinin metin içeriğini string dizisine böler, her bir eleman çerçevedeki ayrı bir metin sütununa karşılık gelir.
type: docs
weight: 144
url: /tr/aspose.slides/textframe/splittextbycolumns/
---
## TextFrame::SplitTextByColumns() metod

[ITextFrame](../../itextframe/) öğesinin metin içeriğini dizi stringlerine böler,  
her bir eleman çerçevedeki ayrı bir metin sütununa karşılık gelir.

```cpp
System::ArrayPtr<System::String> Aspose::Slides::TextFrame::SplitTextByColumns() override
```

### Dönüş Değeri

Bir dizi string, her bir string belirli bir sütunun metin içeriğini temsil eder  
[ITextFrame](../../itextframe/) içinde.

## Açıklamalar

Eğer metin çerçevesi birden fazla sütun içermiyorsa, döndürülen dizi tam metni içeren tek bir eleman  
içerir.  

Boş sütunlar dizi içinde boş stringler olarak temsil edilir.  

Aşağıdaki örnek [TextFrame::SplitTextByColumns](./) nasıl kullanılacağını gösterir:  

```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"example.pptx");

// Slayttaki ilk şekli al ve ITextFrame'e dönüştür
System::SharedPtr<ITextFrame> textFrame = System::AsCast<ITextFrame>(pres->get_Slide(0)->get_Shape(0));
// Metin çerçevesi içeriğini sütunlara böl
System::ArrayPtr<System::String> columnsText = textFrame->SplitTextByColumns();
// Her bir sütunun metnini konsola yazdır
for (System::String column : columnsText)
{
    System::Console::WriteLine(column);
}
```

## Ayrıca Bakınız

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [String](../../../system/string/)
* Class [TextFrame](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)