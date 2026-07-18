---
title: BeginContainer()
second_title: Αναφορά API του Aspose.Slides για C++
description: Αποθηκεύει ένα container με την τρέχουσα κατάσταση αυτού του αντικειμένου, ανοίγει και χρησιμοποιεί ένα νέο container και επιστρέφει το αποθηκευμένο container.
type: docs
weight: 976
url: /el/system.drawing/graphics/begincontainer/
---
## Graphics::BeginContainer() μέθοδος

Αποθηκεύει ένα container με την τρέχουσα κατάσταση αυτού του αντικειμένου, ανοίγει και χρησιμοποιεί ένα νέο container και επιστρέφει το αποθηκευμένο container.

```cpp
SharedPtr<Drawing2D::GraphicsContainer> System::Drawing::Graphics::BeginContainer()
```

## Graphics::BeginContainer(Rectangle, Rectangle, GraphicsUnit) μέθοδος

Αποθηκεύει ένα container με την τρέχουσα κατάσταση αυτού του αντικειμένου, ανοίγει και χρησιμοποιεί ένα νέο container και επιστρέφει το αποθηκευμένο container.

```cpp
SharedPtr<Drawing2D::GraphicsContainer> System::Drawing::Graphics::BeginContainer(Rectangle dstrect, Rectangle srcrect, GraphicsUnit unit)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| dstrect | [Rectangle](../../rectangle/) | Το ορθογώνιο που καθορίζει μια μετασχηματιστική κλίμακα του νέου container. Χρησιμοποιείται μαζί με **srcrect** |
| srcrect | [Rectangle](../../rectangle/) | Το ορθογώνιο που καθορίζει μια μετασχηματιστική κλίμακα του νέου container. Χρησιμοποιείται μαζί με **dstrect** |
| unit | [GraphicsUnit](../../graphicsunit/) | Η τιμή που καθορίζει τη μονάδα μέτρησης του νέου container |

## Graphics::BeginContainer(RectangleF, RectangleF, GraphicsUnit) μέθοδος

Αποθηκεύει ένα container με την τρέχουσα κατάσταση αυτού του αντικειμένου, ανοίγει και χρησιμοποιεί ένα νέο container και επιστρέφει το αποθηκευμένο container.

```cpp
SharedPtr<Drawing2D::GraphicsContainer> System::Drawing::Graphics::BeginContainer(RectangleF dstrect, RectangleF srcrect, GraphicsUnit unit)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| dstrect | [RectangleF](../../rectanglef/) | Το ορθογώνιο που καθορίζει μια μετασχηματιστική κλίμακα του νέου container. Χρησιμοποιείται μαζί με **srcrect** |
| srcrect | [RectangleF](../../rectanglef/) | Το ορθογώνιο που καθορίζει μια μετασχηματιστική κλίμακα του νέου container. Χρησιμοποιείται μαζί με **dstrect** |
| unit | [GraphicsUnit](../../graphicsunit/) | Η τιμή που καθορίζει τη μονάδα μέτρησης του νέου container |

## Δείτε επίσης

* Enum [GraphicsUnit](../../graphicsunit/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [GraphicsContainer](../../../system.drawing.drawing2d/graphicscontainer/)
* Class [Graphics](../)
* Class [Rectangle](../../rectangle/)
* Class [RectangleF](../../rectanglef/)
* Namespace [System::Drawing](../../)
* Library [Aspose.Slides](../../../)