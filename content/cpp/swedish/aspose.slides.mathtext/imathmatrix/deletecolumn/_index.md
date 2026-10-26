---
title: DeleteColumn()
second_title: Aspose.Slides för C++ API-referens
description: Tar bort den angivna kolumnen
type: docs
weight: 339
url: /sv/aspose.slides.mathtext/imathmatrix/deletecolumn/
---
## IMathMatrix::DeleteColumn(int32_t) metod

Tar bort den angivna kolumnen

```cpp
virtual void Aspose::Slides::MathText::IMathMatrix::DeleteColumn(int32_t columnIndex)=0
```


### Argument

| Parameter | Type | Description |
| --- | --- | --- |
| columnIndex | **int32_t** | Det nollbaserade indexet för kolumnen som ska tas bort. |
## Anmärkningar


Exempel: 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->DeleteColumn(0);
```

## Se även

* Klass [IMathMatrix](../)
* Namnrymd [Aspose::Slides::MathText](../../)
* Bibliotek [Aspose.Slides](../../../)