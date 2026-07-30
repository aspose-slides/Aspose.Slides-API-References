---
title: Pen()
second_title: Riferimento API di Aspose.Slides per C++
description: Crea un nuovo oggetto Pen che rappresenta il colore specificato.
type: docs
weight: 1
url: /it/system.drawing/pen/pen/
---
## Pen::Pen(const Color\&) costruttore

Crea un nuovo oggetto [Pen](../) che rappresenta il colore specificato.

```cpp
System::Drawing::Pen::Pen(const Color &color)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| color | const [Color](../../color/)\& | Il colore della penna rappresentata dall'oggetto in costruzione |

## Pen::Pen(const Color\&, float) costruttore

Crea un nuovo oggetto [Pen](../) che rappresenta il colore e la larghezza specificati.

```cpp
System::Drawing::Pen::Pen(const Color &color, float width)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| color | const [Color](../../color/)\& | Il colore della penna rappresentata dall'oggetto in costruzione |
| width | **float** | La larghezza della penna rappresentata dall'oggetto in costruzione |

## Pen::Pen(const SharedPtr\<Brush\>\&) costruttore

Crea un nuovo oggetto [Pen](../) e lo inizializza con l'oggetto [Brush](../../brush/) specificato.

```cpp
System::Drawing::Pen::Pen(const SharedPtr<Brush> &brush)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| brush | const [SharedPtr](../../../system/sharedptr/)\<[Brush](../../brush/)\>\& | L'oggetto [Brush](../../brush/) che specifica le proprietà di riempimento della penna rappresentata dall'oggetto in costruzione |

## Pen::Pen(const SharedPtr\<Brush\>\&, float) costruttore

Crea un nuovo oggetto [Pen](../) e lo inizializza con l'oggetto [Brush](../../brush/) specificato.

```cpp
System::Drawing::Pen::Pen(const SharedPtr<Brush> &brush, float width)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| brush | const [SharedPtr](../../../system/sharedptr/)\<[Brush](../../brush/)\>\& | L'oggetto [Brush](../../brush/) che specifica le proprietà di riempimento della penna rappresentata dall'oggetto in costruzione |
| width | **float** | La larghezza della penna rappresentata dall'oggetto in costruzione |

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [Color](../../color/)
* Classe [Pen](../)
* Classe [Brush](../../brush/)
* Spazio dei nomi [System::Drawing](../../)
* Libreria [Aspose.Slides](../../../)