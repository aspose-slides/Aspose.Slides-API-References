---
title: DrawImage()
second_title: Référence de l'API Aspose.Slides pour C++
description: NON IMPLEMENTÉ.
type: docs
weight: 430
url: /fr/system.drawing/graphics/drawimage/
---
## Graphics::DrawImage(const SharedPtr\<Image\>\&, const System::ArrayPtr\<Point\>\&) méthode


NON IMPLEMENTÉ.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, const System::ArrayPtr<Point> &destPoints)
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | IGNORÉ |
| destPoints | const [System::ArrayPtr](../../../system/arrayptr/)\<[Point](../../point/)\>\& | IGNORÉ |

## Graphics::DrawImage(const SharedPtr\<Image\>\&, const System::ArrayPtr\<PointF\>\&, const RectangleF\&, GraphicsUnit, const Imaging::ImageAttributesPtr\&) méthode


Dessine la région spécifiée de l'image spécifiée à l'emplacement indiqué.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, const System::ArrayPtr<PointF> &destPoints, const RectangleF &srcRect, GraphicsUnit srcUnit, const Imaging::ImageAttributesPtr &imgAttributes)
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | L'image à dessiner |
| destPoints | const [System::ArrayPtr](../../../system/arrayptr/)\<[PointF](../../pointf/)\>\& | Un tableau contenant trois points qui définissent un parallélogramme sur la surface de dessin où dessiner l'image |
| srcRect | const [RectangleF](../../rectanglef/)\& | Un rectangle qui définit la région de l'image spécifiée à dessiner |
| srcUnit | [GraphicsUnit](../../graphicsunit/) | Les unités de mesure utilisées par le paramètre **srcRect** |
| imgAttributes | const [Imaging::ImageAttributesPtr](../../../system.drawing.imaging/imageattributesptr/)\& | Spécifie les informations de couleur et de gamma pour l'image |

## Graphics::DrawImage(const SharedPtr\<Image\>\&, const System::Details::ArrayView\<PointF\>\&, const RectangleF\&, GraphicsUnit, const Imaging::ImageAttributesPtr\&) méthode


Dessine la région spécifiée de l'image spécifiée à l'emplacement indiqué.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, const System::Details::ArrayView<PointF> &destPoints, const RectangleF &srcRect, GraphicsUnit srcUnit, const Imaging::ImageAttributesPtr &imgAttributes)
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | L'image à dessiner |
| destPoints | const System::Details::ArrayView\<[PointF](../../pointf/)\>\& | Une vue de tableau contenant trois points qui définissent un parallélogramme sur la surface de dessin où dessiner l'image |
| srcRect | const [RectangleF](../../rectanglef/)\& | Un rectangle qui définit la région de l'image spécifiée à dessiner |
| srcUnit | [GraphicsUnit](../../graphicsunit/) | Les unités de mesure utilisées par le paramètre **srcRect** |
| imgAttributes | const [Imaging::ImageAttributesPtr](../../../system.drawing.imaging/imageattributesptr/)\& | Spécifie les informations de couleur et de gamma pour l'image |

## Graphics::DrawImage(const SharedPtr\<Image\>\&, const System::Details::StackArray\<PointF, N\>\&, const RectangleF\&, GraphicsUnit, const Imaging::ImageAttributesPtr\&) méthode


Dessine la région spécifiée de l'image spécifiée à l'emplacement indiqué.

```cpp
template<std::size_t> void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, const System::Details::StackArray<PointF, N> &destPoints, const RectangleF &srcRect, GraphicsUnit srcUnit, const Imaging::ImageAttributesPtr &imgAttributes)
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | L'image à dessiner |
| destPoints | const System::Details::StackArray\<[PointF](../../pointf/), N\>\& | Un tableau empilé contenant trois points qui définissent un parallélogramme sur la surface de dessin où dessiner l'image |
| srcRect | const [RectangleF](../../rectanglef/)\& | Un rectangle qui définit la région de l'image spécifiée à dessiner |
| srcUnit | [GraphicsUnit](../../graphicsunit/) | Les unités de mesure utilisées par le paramètre **srcRect** |
| imgAttributes | const [Imaging::ImageAttributesPtr](../../../system.drawing.imaging/imageattributesptr/)\& | Spécifie les informations de couleur et de gamma pour l'image |

## Graphics::DrawImage(const SharedPtr\<Image\>\&, int, int) méthode


Dessine l'image spécifiée à l'emplacement indiqué.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, int x, int y)
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | L'image à dessiner |
| x | int | La coordonnée X du coin supérieur gauche de l'image dessinée |
| y | int | La coordonnée Y du coin supérieur gauche de l'image dessinée |

## Graphics::DrawImage(const SharedPtr\<Image\>\&, float, float) méthode


Dessine l'image spécifiée à l'emplacement indiqué.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, float x, float y)
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | L'image à dessiner |
| x | **float** | La coordonnée X du coin supérieur gauche de l'image dessinée |
| y | **float** | La coordonnée Y du coin supérieur gauche de l'image dessinée |

## Graphics::DrawImage(const SharedPtr\<Image\>\&, Point) méthode


Dessine l'image spécifiée à l'emplacement indiqué.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, Point pt)
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | L'image à dessiner |
| pt | [Point](../../point/) | L'emplacement du coin supérieur gauche de l'image dessinée |

## Graphics::DrawImage(const SharedPtr\<Image\>\&, PointF) méthode


Dessine l'image spécifiée à l'emplacement indiqué.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, PointF pt)
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | L'image à dessiner |
| pt | [PointF](../../pointf/) | L'emplacement du coin supérieur gauche de l'image dessinée |

## Graphics::DrawImage(const SharedPtr\<Image\>\&, int, int, int, int) méthode


Dessine l'image spécifiée dans le rectangle indiqué.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, int x, int y, int width, int height)
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | L'image à dessiner |
| x | int | La coordonnée X du coin supérieur gauche du rectangle où dessiner l'image |
| y | int | La coordonnée Y du coin supérieur gauche du rectangle où dessiner l'image |
| width | int | La largeur du rectangle où dessiner l'image |
| height | int | La hauteur du rectangle où dessiner l'image |

## Graphics::DrawImage(const SharedPtr\<Image\>\&, float, float, float, float) méthode


Dessine l'image spécifiée dans le rectangle indiqué.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, float x, float y, float width, float height)
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | L'image à dessiner |
| x | **float** | La coordonnée X du coin supérieur gauche du rectangle où dessiner l'image |
| y | **float** | La coordonnée Y du coin supérieur gauche du rectangle où dessiner l'image |
| width | **float** | La largeur du rectangle où dessiner l'image |
| height | **float** | La hauteur du rectangle où dessiner l'image |

## Graphics::DrawImage(const SharedPtr\<Image\>\&, RectangleF, RectangleF, GraphicsUnit) méthode


Dessine la région spécifiée de l'image spécifiée à l'emplacement indiqué.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, RectangleF destRect, RectangleF srcRect, GraphicsUnit srcUnit)
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | L'image à dessiner |
| destRect | [RectangleF](../../rectanglef/) | Un rectangle où dessiner l'image |
| srcRect | [RectangleF](../../rectanglef/) | Un rectangle qui définit la région de l'image spécifiée à dessiner |
| srcUnit | [GraphicsUnit](../../graphicsunit/) | Les unités de mesure utilisées par le paramètre **srcRect** |

## Graphics::DrawImage(const SharedPtr\<Image\>\&, Rectangle, Rectangle, GraphicsUnit) méthode


Dessine la région spécifiée de l'image spécifiée à l'emplacement indiqué.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, Rectangle destRect, Rectangle srcRect, GraphicsUnit srcUnit)
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | L'image à dessiner |
| destRect | [Rectangle](../../rectangle/) | Un rectangle où dessiner l'image |
| srcRect | [Rectangle](../../rectangle/) | Un rectangle qui définit la région de l'image spécifiée à dessiner |
| srcUnit | [GraphicsUnit](../../graphicsunit/) | Les unités de mesure utilisées par le paramètre **srcRect** |

## Graphics::DrawImage(const SharedPtr\<Image\>\&, int, int, Rectangle, GraphicsUnit) méthode


Dessine la région spécifiée de l'image spécifiée à l'emplacement indiqué.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, int x, int y, Rectangle srcRect, GraphicsUnit srcUnit)
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | L'image à dessiner |
| x | int | La coordonnée X du coin supérieur gauche du rectangle où dessiner l'image |
| y | int | La coordonnée Y du coin supérieur gauche du rectangle où dessiner l'image |
| srcRect | [Rectangle](../../rectangle/) | Un rectangle qui définit la région de l'image spécifiée à dessiner |
| srcUnit | [GraphicsUnit](../../graphicsunit/) | Les unités de mesure utilisées par le paramètre **srcRect** |

## Graphics::DrawImage(const SharedPtr\<Image\>\&, const Rectangle\&) méthode


Dessine l'image spécifiée à l'emplacement indiqué.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, const Rectangle &rect)
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | L'image à dessiner |
| rect | const [Rectangle](../../rectangle/)\& | Un rectangle où dessiner l'image |

## Graphics::DrawImage(const SharedPtr\<Image\>\&, const RectangleF\&) méthode


Dessine l'image spécifiée à l'emplacement indiqué.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, const RectangleF &rect)
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | L'image à dessiner |
| rect | const [RectangleF](../../rectanglef/)\& | Un rectangle où dessiner l'image |

## Graphics::DrawImage(const SharedPtr\<Image\>\&, Rectangle, int, int, int, int, GraphicsUnit, const Imaging::ImageAttributesPtr\&) méthode


Dessine la région spécifiée de l'image spécifiée dans le rectangle indiqué.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, Rectangle destRect, int srcX, int srcY, int srcWidth, int srcHeight, GraphicsUnit srcUnit, const Imaging::ImageAttributesPtr &imgAttributes)
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | L'image à dessiner |
| destRect | [Rectangle](../../rectangle/) | Un rectangle où dessiner l'image |
| srcX | int | La coordonnée X du coin supérieur gauche du rectangle qui indique la partie de l'image à dessiner |
| srcY | int | La coordonnée Y du coin supérieur gauche du rectangle qui indique la partie de l'image à dessiner |
| srcWidth | int | La largeur du coin supérieur gauche du rectangle qui indique la partie de l'image à dessiner |
| srcHeight | int | La hauteur du coin supérieur gauche du rectangle qui indique la partie de l'image à dessiner |
| srcUnit | [GraphicsUnit](../../graphicsunit/) | Les unités de mesure dans lesquelles les paramètres **srcX**, **srcY**, **srcWidth** et **srcHeight** sont spécifiés |
| imgAttributes | const [Imaging::ImageAttributesPtr](../../../system.drawing.imaging/imageattributesptr/)\& | Spécifie les informations de couleur et de gamma pour l'image |

## Graphics::DrawImage(const SharedPtr\<Image\>\&, Rectangle, float, float, float, float, GraphicsUnit, const Imaging::ImageAttributesPtr\&) méthode


Dessine la région spécifiée de l'image spécifiée dans le rectangle indiqué.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, Rectangle destRect, float srcX, float srcY, float srcWidth, float srcHeight, GraphicsUnit srcUnit, const Imaging::ImageAttributesPtr &imgAttributes)
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | L'image à dessiner |
| destRect | [Rectangle](../../rectangle/) | Un rectangle où dessiner l'image |
| srcX | **float** | La coordonnée X du coin supérieur gauche du rectangle qui indique la partie de l'image à dessiner |
| srcY | **float** | La coordonnée Y du coin supérieur gauche du rectangle qui indique la partie de l'image à dessiner |
| srcWidth | **float** | La largeur du coin supérieur gauche du rectangle qui indique la partie de l'image à dessiner |
| srcHeight | **float** | La hauteur du coin supérieur gauche du rectangle qui indique la partie de l'image à dessiner |
| srcUnit | [GraphicsUnit](../../graphicsunit/) | Les unités de mesure dans lesquelles les paramètres **srcX**, **srcY**, **srcWidth** et **srcHeight** sont spécifiés |
| imgAttributes | const [Imaging::ImageAttributesPtr](../../../system.drawing.imaging/imageattributesptr/)\& | Spécifie les informations de couleur et de gamma pour l'image |

## Graphics::DrawImage(const SharedPtr\<Image\>\&, Rectangle, int, int, int, int, GraphicsUnit) méthode


Dessine la région spécifiée de l'image spécifiée dans le rectangle indiqué.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, Rectangle destRect, int srcX, int srcY, int srcWidth, int srcHeight, GraphicsUnit srcUnit)
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | L'image à dessiner |
| destRect | [Rectangle](../../rectangle/) | Un rectangle où dessiner l'image |
| srcX | int | La coordonnée X du coin supérieur gauche du rectangle qui indique la partie de l'image à dessiner |
| srcY | int | La coordonnée Y du coin supérieur gauche du rectangle qui indique la partie de l'image à dessiner |
| srcWidth | int | La largeur du coin supérieur gauche du rectangle qui indique la partie de l'image à dessiner |
| srcHeight | int | La hauteur du coin supérieur gauche du rectangle qui indique la partie de l'image à dessiner |
| srcUnit | [GraphicsUnit](../../graphicsunit/) | Les unités de mesure dans lesquelles les paramètres **srcX**, **srcY**, **srcWidth** et **srcHeight** sont spécifiés |

## Graphics::DrawImage(const SharedPtr\<Image\>\&, Rectangle, float, float, float, float, GraphicsUnit) méthode


Dessine la région spécifiée de l'image spécifiée dans le rectangle indiqué.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, Rectangle destRect, float srcX, float srcY, float srcWidth, float srcHeight, GraphicsUnit srcUnit)
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | L'image à dessiner |
| destRect | [Rectangle](../../rectangle/) | Un rectangle où dessiner l'image |
| srcX | **float** | La coordonnée X du coin supérieur gauche du rectangle qui indique la partie de l'image à dessiner |
| srcY | **float** | La coordonnée Y du coin supérieur gauche du rectangle qui indique la partie de l'image à dessiner |
| srcWidth | **float** | La largeur du coin supérieur gauche du rectangle qui indique la partie de l'image à dessiner |
| srcHeight | **float** | La hauteur du coin supérieur gauche du rectangle qui indique la partie de l'image à dessiner |
| srcUnit | [GraphicsUnit](../../graphicsunit/) | Les unités de mesure dans lesquelles les paramètres **srcX**, **srcY**, **srcWidth** et **srcHeight** sont spécifiés |

## Graphics::DrawImage(const SharedPtr\<Image\>\&, Rectangle, int, int, int, int, GraphicsUnit, const Imaging::ImageAttributesPtr\&, Graphics::DrawImageAbort) méthode


NON IMPLEMENTÉ.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, Rectangle destRect, int srcX, int srcY, int srcWidth, int srcHeight, GraphicsUnit srcUnit, const Imaging::ImageAttributesPtr &imgAttributes, Graphics::DrawImageAbort callback)
```


## Graphics::DrawImage(const SharedPtr\<Image\>\&, Rectangle, float, float, float, float, GraphicsUnit, const Imaging::ImageAttributesPtr\&, Graphics::DrawImageAbort) méthode


NON IMPLEMENTÉ.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, Rectangle destRect, float srcX, float srcY, float srcWidth, float srcHeight, GraphicsUnit srcUnit, const Imaging::ImageAttributesPtr &imgAttributes, Graphics::DrawImageAbort callback)
```


## Graphics::DrawImage(const SharedPtr\<Image\>\&, Rectangle, int, int, int, int, GraphicsUnit, const Imaging::ImageAttributesPtr\&, Graphics::DrawImageAbort, IntPtr) méthode


NON IMPLEMENTÉ.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, Rectangle destRect, int srcX, int srcY, int srcWidth, int srcHeight, GraphicsUnit srcUnit, const Imaging::ImageAttributesPtr &imgAttributes, Graphics::DrawImageAbort callback, IntPtr callbackData)
```


## Graphics::DrawImage(const SharedPtr\<Image\>\&, Rectangle, float, float, float, float, GraphicsUnit, const Imaging::ImageAttributesPtr\&, Graphics::DrawImageAbort, IntPtr) méthode


NON IMPLEMENTÉ.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, Rectangle destRect, float srcX, float srcY, float srcWidth, float srcHeight, GraphicsUnit srcUnit, const Imaging::ImageAttributesPtr &imgAttributes, Graphics::DrawImageAbort callback, IntPtr callbackData)
```


## Graphics::DrawImage(const SharedPtr\<Image\>\&, const ArrayPtr\<PointF\>\&, RectangleF, GraphicsUnit) méthode


NON IMPLEMENTÉ.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, const ArrayPtr<PointF> &destPoints, RectangleF srcRect, GraphicsUnit srcUnit)
```


## Graphics::DrawImage(const SharedPtr\<Image\>\&, const ArrayPtr\<PointF\>\&) méthode


NON IMPLEMENTÉ.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, const ArrayPtr<PointF> &destPoints)
```


## Graphics::DrawImage(const SharedPtr\<Image\>\&, const ArrayPtr\<Point\>\&, Rectangle, GraphicsUnit) méthode


NON IMPLEMENTÉ.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, const ArrayPtr<Point> &destPoints, Rectangle srcRect, GraphicsUnit srcUnit)
```


## Graphics::DrawImage(const SharedPtr\<Image\>\&, const ArrayPtr\<Point\>\&, Rectangle, GraphicsUnit, const SharedPtr\<Imaging::ImageAttributes\>\&) méthode


Dessine la région spécifiée de l'image spécifiée à l'emplacement indiqué.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, const ArrayPtr<Point> &destPoints, Rectangle srcRect, GraphicsUnit srcUnit, const SharedPtr<Imaging::ImageAttributes> &imageAttr)
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | L'image à dessiner |
| destPoints | const [ArrayPtr](../../../system/arrayptr/)\<[Point](../../point/)\>\& | Un tableau contenant trois points qui définissent un parallélogramme sur la surface de dessin où dessiner l'image |
| srcRect | [Rectangle](../../rectangle/) | Un rectangle qui définit la région de l'image spécifiée à dessiner |
| srcUnit | [GraphicsUnit](../../graphicsunit/) | Les unités de mesure utilisées par le paramètre **srcRect** |
| imageAttr | const [SharedPtr](../../../system/sharedptr/)\<[Imaging::ImageAttributes](../../../system.drawing.imaging/imageattributes/)\>\& | Spécifie les informations de couleur et de gamma pour l'image |

## Graphics::DrawImage(const SharedPtr\<Image\>\&, float, float, RectangleF, GraphicsUnit) méthode


Dessine la région spécifiée de l'image spécifiée à l'emplacement indiqué.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, float x, float y, RectangleF srcRect, GraphicsUnit srcUnit)
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | L'image à dessiner |
| x | **float** | La coordonnée X du coin supérieur gauche du rectangle où dessiner l'image |
| y | **float** | La coordonnée Y du coin supérieur gauche du rectangle où dessiner l'image |
| srcRect | [RectangleF](../../rectanglef/) | Un rectangle qui définit la région de l'image spécifiée à dessiner |
| srcUnit | [GraphicsUnit](../../graphicsunit/) | Les unités de mesure utilisées par le paramètre **srcRect** |

## Voir aussi

* Énum [GraphicsUnit](../../graphicsunit/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [ImageAttributesPtr](../../../system.drawing.imaging/imageattributesptr/)
* Typedef [DrawImageAbort](../drawimageabort/)
* Classe [Image](../../image/)
* Classe [Point](../../point/)
* Classe [Graphics](../)
* Classe [PointF](../../pointf/)
* Classe [RectangleF](../../rectanglef/)
* Classe [Rectangle](../../rectangle/)
* Classe [ImageAttributes](../../../system.drawing.imaging/imageattributes/)
* Espace de noms [System::Drawing](../../)
* Bibliothèque [Aspose.Slides](../../../)