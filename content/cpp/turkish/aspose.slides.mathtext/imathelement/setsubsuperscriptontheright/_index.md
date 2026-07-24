---
title: SetSubSuperscriptOnTheRight()
second_title: Aspose.Slides for C++ API Referansı
description: Sağ tarafta alt ve üst indis oluşturur
type: docs
weight: 105
url: /tr/aspose.slides.mathtext/imathelement/setsubsuperscriptontheright/
---
## IMathElement::SetSubSuperscriptOnTheRight(System::SharedPtr\<IMathElement\>, System::SharedPtr\<IMathElement\>) metodu


Sağ tarafta alt ve üst indeks oluşturur

```cpp
virtual System::SharedPtr<IMathRightSubSuperscriptElement> Aspose::Slides::MathText::IMathElement::SetSubSuperscriptOnTheRight(System::SharedPtr<IMathElement> subscript, System::SharedPtr<IMathElement> superscript)=0
```


### Arguments

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| subscript | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../)\> | Alt indis (sağ tarafta alt indis) |
| superscript | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../)\> | Üst indis (sağ tarafta üst indis) |

### Return Value

Yeni [IMathRightSubSuperscriptElement](../../imathrightsubsuperscriptelement/) tipinde matematik öğesi
## Remarks



Örnek: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"N");
auto subscript = System::MakeObject<MathematicalText>(u"i");
auto superscript = System::MakeObject<MathematicalText>(u"j");
auto subsuperscript = baseElement->SetSubSuperscriptOnTheRight(subscript, superscript);
```

## IMathElement::SetSubSuperscriptOnTheRight(System::String, System::String) metodu


Sağ tarafta alt ve üst indeks oluşturur

```cpp
virtual System::SharedPtr<IMathRightSubSuperscriptElement> Aspose::Slides::MathText::IMathElement::SetSubSuperscriptOnTheRight(System::String subscript, System::String superscript)=0
```


### Arguments

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| subscript | [System::String](../../../system/string/) | Alt indis (sağ tarafta alt indis) |
| superscript | [System::String](../../../system/string/) | Üst indis (sağ tarafta üst indis) |

### Return Value

Yeni [IMathRightSubSuperscriptElement](../../imathrightsubsuperscriptelement/) tipinde matematik öğesi
## Remarks



Örnek: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"N");
auto subsuperscript = baseElement->SetSubSuperscriptOnTheRight(u"i", u"j");
```

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IMathRightSubSuperscriptElement](../../imathrightsubsuperscriptelement/)
* Class [IMathElement](../)
* Class [String](../../../system/string/)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)