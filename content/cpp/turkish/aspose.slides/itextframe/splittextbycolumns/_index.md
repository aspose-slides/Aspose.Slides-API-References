---
title: SplitTextByColumns()
second_title: Aspose.Slides for C++ API Referansı
description: ITextFrame'in metin içeriğini dizeler dizisine böler, her eleman çerçevedeki ayrı bir metin sütununa karşılık gelir.
type: docs
weight: 118
url: /tr/aspose.slides/itextframe/splittextbycolumns/
---
## ITextFrame::SplitTextByColumns() metodu


[ITextFrame](../) öğesinin metin içeriğini dize dizisine böler, 

 her öğe çerçevedeki ayrı bir metin sütununa karşılık gelir.

```cpp
virtual System::ArrayPtr<System::String> Aspose::Slides::ITextFrame::SplitTextByColumns()=0
```


### Dönüş Değeri

Dize dizisi, her dize belirli bir sütunun metin içeriğini temsil eder 

 [ITextFrame](../) içinde.

## Açıklamalar



Eğer metin çerçevesi birden çok sütun içermiyorsa, döndürülen dizi tam metni içeren tek bir öğeye sahip olacaktır. 

 Boş sütunlar dizide boş dize olarak temsil edilir. 

Aşağıdaki örnek [ITextFrame::SplitTextByColumns](./) kullanımını gösterir: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"example.pptx");

// Slayttaki ilk şekli al ve ITextFrame'e dönüştür
System::SharedPtr<ITextFrame> textFrame = System::AsCast<ITextFrame>(pres->get_Slide(0)->get_Shape(0));
// Metin çerçevesi içeriğini sütunlara böl
System::ArrayPtr<System::String> columnsText = textFrame->SplitTextByColumns();
// Her sütunun metnini konsola yazdır
for (System::String column : columnsText)
{
    System::Console::WriteLine(column);
}
```

## Ayrıca Bakınız

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Sınıf [String](../../../system/string/)
* Sınıf [ITextFrame](../)
* Ad alanı [Aspose::Slides](../../)
* Kütüphane [Aspose.Slides](../../../)