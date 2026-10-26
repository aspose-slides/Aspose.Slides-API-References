---  
title: idx_set()  
second_title: Αναφορά API του Aspose.Slides για C++  
description: Στοιχεία του πίνακα  
type: docs  
weight: 222  
url: /el/aspose.slides.mathtext/imathmatrix/idx_set/  
---
## IMathMatrix::idx_set(int32_t, int32_t, System::SharedPtr\<IMathElement\>) method


Στοιχεία του πίνακα

```cpp
virtual void Aspose::Slides::MathText::IMathMatrix::idx_set(int32_t row, int32_t column, System::SharedPtr<IMathElement> value)=0
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| row | **int32_t** | Ο μηδενικός δείκτης της γραμμής για λήψη του στοιχείου |
| column | **int32_t** | Ο μηδενικός δείκτης της στήλης για λήψη του στοιχείου |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> |  |
## Remarks



Παράδειγμα: 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->idx_set(0, 0, System::MakeObject<MathematicalText>(u"item.1.1"));
```

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Κλάση [IMathElement](../../imathelement/)
* Κλάση [IMathMatrix](../)
* Χώρος ονομάτων [Aspose::Slides::MathText](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)