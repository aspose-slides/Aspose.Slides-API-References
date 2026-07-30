---
title: MeasureString()
second_title: Riferimento API Aspose.Slides per C++
description: Restituisce la dimensione della stringa specificata quando viene disegnata con il carattere specificato nel formato specificato.
type: docs
weight: 521
url: /it/system.drawing/graphics/measurestring/
---
## Graphics::MeasureString(String const\&, System::SharedPtr\<Font\> const\&, PointF const\&, System::SharedPtr\<StringFormat\> const\&) const metodo


Restituisce la dimensione della stringa specificata quando viene disegnata con il carattere specificato nel formato specificato.

```cpp
SizeF System::Drawing::Graphics::MeasureString(String const &str, System::SharedPtr<Font> const &font, PointF const &origin=PointF(0, 0), System::SharedPtr<StringFormat> const &stringFormat=nullptr) const
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| str | [String](../../../system/string/) const\& | La stringa di cui calcolare la dimensione |
| font | [System::SharedPtr](../../../system/sharedptr/)\<[Font](../../font/)\> const\& | Il carattere usato per disegnare la stringa |
| origin | [PointF](../../pointf/) const\& | Specifica la posizione dell'angolo superiore sinistro della stringa |
| stringFormat | [System::SharedPtr](../../../system/sharedptr/)\<[StringFormat](../../stringformat/)\> const\& | Specifica il formato della stringa |

### Valore di ritorno

Un oggetto [SizeF](../../sizef/) che rappresenta la dimensione della stringa nelle unità di misura specificate dalla proprietà PageUnit dell'oggetto Graphics corrente.

## Graphics::MeasureString(String const\&, System::SharedPtr\<Font\> const\&, int, System::SharedPtr\<StringFormat\> const\&) const metodo


Restituisce la dimensione della stringa specificata quando viene disegnata con il carattere specificato nel formato specificato.

```cpp
SizeF System::Drawing::Graphics::MeasureString(String const &str, System::SharedPtr<Font> const &font, int width, System::SharedPtr<StringFormat> const &stringFormat=nullptr) const
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| str | [String](../../../system/string/) const\& | La stringa di cui calcolare la dimensione |
| font | [System::SharedPtr](../../../system/sharedptr/)\<[Font](../../font/)\> const\& | Il carattere usato per disegnare la stringa |
| width | int | La larghezza massima della stringa |
| stringFormat | [System::SharedPtr](../../../system/sharedptr/)\<[StringFormat](../../stringformat/)\> const\& | Specifica il formato della stringa |

### Valore di ritorno

Un oggetto [SizeF](../../sizef/) che rappresenta la dimensione della stringa nelle unità di misura specificate dalla proprietà PageUnit dell'oggetto Graphics corrente.

## Graphics::MeasureString(String const\&, System::SharedPtr\<Font\> const\&, SizeF const\&, System::SharedPtr\<StringFormat\> const\&, int\&, int\&) const metodo


NON IMPLEMENTATO.

```cpp
SizeF System::Drawing::Graphics::MeasureString(String const &str, System::SharedPtr<Font> const &font, SizeF const &layoutArea, System::SharedPtr<StringFormat> const &stringFormat, int &charactersFitted, int &linesFilled) const
```


## Graphics::MeasureString(String const\&, System::SharedPtr\<Font\> const\&, SizeF const\&, System::SharedPtr\<StringFormat\> const\&) const metodo


Restituisce la dimensione della stringa specificata quando viene disegnata con il carattere specificato nel formato specificato.

```cpp
SizeF System::Drawing::Graphics::MeasureString(String const &str, System::SharedPtr<Font> const &font, SizeF const &layoutArea, System::SharedPtr<StringFormat> const &stringFormat=nullptr) const
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| str | [String](../../../system/string/) const\& | La stringa di cui calcolare la dimensione |
| font | [System::SharedPtr](../../../system/sharedptr/)\<[Font](../../font/)\> const\& | Il carattere usato per disegnare la stringa |
| layoutArea | [SizeF](../../sizef/) const\& | L'area di layout massima della stringa |
| stringFormat | [System::SharedPtr](../../../system/sharedptr/)\<[StringFormat](../../stringformat/)\> const\& | Specifica il formato della stringa |

### Valore di ritorno

Un oggetto [SizeF](../../sizef/) che rappresenta la dimensione della stringa nelle unità di misura specificate dalla proprietà PageUnit dell'oggetto Graphics corrente.

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [SizeF](../../sizef/)
* Classe [String](../../../system/string/)
* Classe [Font](../../font/)
* Classe [PointF](../../pointf/)
* Classe [StringFormat](../../stringformat/)
* Classe [Graphics](../)
* Namespace [System::Drawing](../../)
* Libreria [Aspose.Slides](../../../)