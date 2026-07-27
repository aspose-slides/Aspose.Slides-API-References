---
title: Pen()
second_title: Referência da API Aspose.Slides para C++
description: Constrói um novo objeto Pen que representa a cor especificada.
type: docs
weight: 1
url: /pt/system.drawing/pen/pen/
---
## Pen::Pen(const Color\&) construtor

Constrói um novo objeto [Pen](../) que representa a cor especificada.

```cpp
System::Drawing::Pen::Pen(const Color &color)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| color | const [Color](../../color/)\& | A cor da caneta representada pelo objeto que está sendo construído |

## Pen::Pen(const Color\&, float) construtor

Constrói um novo objeto [Pen](../) que representa a cor e a largura especificadas.

```cpp
System::Drawing::Pen::Pen(const Color &color, float width)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| color | const [Color](../../color/)\& | A cor da caneta representada pelo objeto que está sendo construído |
| width | **float** | A largura da caneta representada pelo objeto que está sendo construído |

## Pen::Pen(const SharedPtr\<Brush\>\&) construtor

Constrói um novo objeto [Pen](../) e o inicializa com o objeto [Brush](../../brush/) especificado.

```cpp
System::Drawing::Pen::Pen(const SharedPtr<Brush> &brush)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| brush | const [SharedPtr](../../../system/sharedptr/)\<[Brush](../../brush/)\>\& | O objeto [Brush](../../brush/) que especifica as propriedades de preenchimento da caneta representada pelo objeto que está sendo construído |

## Pen::Pen(const SharedPtr\<Brush\>\&, float) construtor

Constrói um novo objeto [Pen](../) e o inicializa com o objeto [Brush](../../brush/) especificado.

```cpp
System::Drawing::Pen::Pen(const SharedPtr<Brush> &brush, float width)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| brush | const [SharedPtr](../../../system/sharedptr/)\<[Brush](../../brush/)\>\& | O objeto [Brush](../../brush/) que especifica as propriedades de preenchimento da caneta representada pelo objeto que está sendo construído |
| width | **float** | A largura da caneta representada pelo objeto que está sendo construído |

## Veja Também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [Color](../../color/)
* Classe [Pen](../)
* Classe [Brush](../../brush/)
* Namespace [System::Drawing](../../)
* Biblioteca [Aspose.Slides](../../../)