---
title: DrawString()
second_title: Riferimento API di Aspose.Slides per C++
description: Disegna la stringa specificata nella posizione specificata usando il font e il pennello specificati.
type: docs
weight: 365
url: /it/system.drawing/graphics/drawstring/
---
## Graphics::DrawString(const String\&, const SharedPtr\<Font\>\&, const SharedPtr\<Brush\>\&, PointF, const System::SharedPtr\<System::Drawing::StringFormat\>\&) metodo


Disegna la stringa specificata nella posizione specificata usando il font e il pennello specificati.

```cpp
void System::Drawing::Graphics::DrawString(const String &str, const SharedPtr<Font> &font, const SharedPtr<Brush> &brush, PointF topLeft, const System::SharedPtr<System::Drawing::StringFormat> &stringFormat=nullptr)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| str | const [String](../../../system/string/)\& | La stringa da disegnare |
| font | const [SharedPtr](../../../system/sharedptr/)\<[Font](../../font/)\>\& | Un font da utilizzare |
| brush | const [SharedPtr](../../../system/sharedptr/)\<[Brush](../../brush/)\>\& | Un [Brush](../../brush/) oggetto da utilizzare per il disegno |
| topLeft | [PointF](../../pointf/) | Specifica la posizione dell'angolo superiore sinistro della stringa disegnata |
| stringFormat | const [System::SharedPtr](../../../system/sharedptr/)\<[System::Drawing::StringFormat](../../stringformat/)\>\& | Specifica il formato della stringa |

## Graphics::DrawString(const String\&, const SharedPtr\<Font\>\&, const SharedPtr\<Brush\>\&, RectangleF, const System::SharedPtr\<System::Drawing::StringFormat\>\&) metodo


Disegna la stringa specificata nel rettangolo specificato usando il font e il pennello specificati.

```cpp
void System::Drawing::Graphics::DrawString(const String &str, const SharedPtr<Font> &font, const SharedPtr<Brush> &brush, RectangleF layoutRectangle, const System::SharedPtr<System::Drawing::StringFormat> &stringFormat=nullptr)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| str | const [String](../../../system/string/)\& | La stringa da disegnare |
| font | const [SharedPtr](../../../system/sharedptr/)\<[Font](../../font/)\>\& | Un font da utilizzare |
| brush | const [SharedPtr](../../../system/sharedptr/)\<[Brush](../../brush/)\>\& | Un [Brush](../../brush/) oggetto da utilizzare per il disegno |
| layoutRectangle | [RectangleF](../../rectanglef/) | Specifica un rettangolo in cui disegnare la stringa |
| stringFormat | const [System::SharedPtr](../../../system/sharedptr/)\<[System::Drawing::StringFormat](../../stringformat/)\>\& | Specifica il formato della stringa |

## Graphics::DrawString(const String\&, const SharedPtr\<Font\>\&, const SharedPtr\<Brush\>\&, float, float, const System::SharedPtr\<System::Drawing::StringFormat\>\&) metodo


Disegna la stringa specificata nella posizione specificata usando il font e il pennello specificati.

```cpp
void System::Drawing::Graphics::DrawString(const String &str, const SharedPtr<Font> &font, const SharedPtr<Brush> &brush, float x, float y, const System::SharedPtr<System::Drawing::StringFormat> &stringFormat=nullptr)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| str | const [String](../../../system/string/)\& | La stringa da disegnare |
| font | const [SharedPtr](../../../system/sharedptr/)\<[Font](../../font/)\>\& | Un font da utilizzare |
| brush | const [SharedPtr](../../../system/sharedptr/)\<[Brush](../../brush/)\>\& | Un [Brush](../../brush/) oggetto da utilizzare per il disegno |
| x | **float** | La coordinata X della posizione dell'angolo superiore sinistro della stringa disegnata |
| y | **float** | La coordinata Y della posizione dell'angolo superiore sinistro della stringa disegnata |
| stringFormat | const [System::SharedPtr](../../../system/sharedptr/)\<[System::Drawing::StringFormat](../../stringformat/)\>\& | Specifica il formato della stringa |

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [String](../../../system/string/)
* Classe [Font](../../font/)
* Classe [Brush](../../brush/)
* Classe [PointF](../../pointf/)
* Classe [StringFormat](../../stringformat/)
* Classe [Graphics](../)
* Classe [RectangleF](../../rectanglef/)
* Spazio dei nomi [System::Drawing](../../)
* Libreria [Aspose.Slides](../../../)