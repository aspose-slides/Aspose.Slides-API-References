---
title: Pen()
second_title: Referencia de la API de Aspose.Slides para C++
description: Construye un nuevo objeto Pen que representa el color especificado.
type: docs
weight: 1
url: /es/system.drawing/pen/pen/
---
## Pen::Pen(const Color\&) constructor

Construye un nuevo objeto [Pen](../) que representa el color especificado.

```cpp
System::Drawing::Pen::Pen(const Color &color)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| color | const [Color](../../color/)\& | El color de la pluma representada por el objeto que se está construyendo |

## Pen::Pen(const Color\&, float) constructor

Construye un nuevo objeto [Pen](../) que representa el color y el ancho especificados.

```cpp
System::Drawing::Pen::Pen(const Color &color, float width)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| color | const [Color](../../color/)\& | El color de la pluma representada por el objeto que se está construyendo |
| width | **float** | El ancho de la pluma representada por el objeto que se está construyendo |

## Pen::Pen(const SharedPtr\<Brush\>\&) constructor

Construye un nuevo objeto [Pen](../) y lo inicializa con el objeto [Brush](../../brush/) especificado.

```cpp
System::Drawing::Pen::Pen(const SharedPtr<Brush> &brush)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| brush | const [SharedPtr](../../../system/sharedptr/)\<[Brush](../../brush/)\>\& | El objeto [Brush](../../brush/) que especifica las propiedades de relleno de la pluma representada por el objeto que se está construyendo |

## Pen::Pen(const SharedPtr\<Brush\>\&, float) constructor

Construye un nuevo objeto [Pen](../) y lo inicializa con el objeto [Brush](../../brush/) especificado.

```cpp
System::Drawing::Pen::Pen(const SharedPtr<Brush> &brush, float width)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| brush | const [SharedPtr](../../../system/sharedptr/)\<[Brush](../../brush/)\>\& | El objeto [Brush](../../brush/) que especifica las propiedades de relleno de la pluma representada por el objeto que se está construyendo |
| width | **float** | El ancho de la pluma representada por el objeto que se está construyendo |

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [Color](../../color/)
* Clase [Pen](../)
* Clase [Brush](../../brush/)
* Espacio de nombres [System::Drawing](../../)
* Biblioteca [Aspose.Slides](../../../)