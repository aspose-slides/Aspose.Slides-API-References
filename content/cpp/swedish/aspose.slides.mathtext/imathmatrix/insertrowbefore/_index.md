---
title: InsertRowBefore()
second_title: Aspose.Slides för C++ API-referens
description: Infoga en ny rad före den angivna. Alla element i den nya raden är initialt null.
type: docs
weight: 274
url: /sv/aspose.slides.mathtext/imathmatrix/insertrowbefore/
---
## IMathMatrix::InsertRowBefore(int32_t) method


Infoga en ny rad före den angivna. Alla element i den nya raden är initialt null.

```cpp
virtual void Aspose::Slides::MathText::IMathMatrix::InsertRowBefore(int32_t rowIndex)=0
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| rowIndex | **int32_t** | Index för raden innan vilken en ny ska infogas |
## Remarks



Exempel: 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->InsertRowBefore(1);
```

## Se även

* Klass [IMathMatrix](../)
* Namnrymd [Aspose::Slides::MathText](../../)
* Bibliotek [Aspose.Slides](../../../)