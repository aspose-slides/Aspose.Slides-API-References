---
title: FromStream()
second_title: Riferimento API Aspose.Slides per C++
description: Crea un oggetto Image dal flusso specificato.
type: docs
weight: 339
url: /it/system.drawing/image/fromstream/
---
## Image::FromStream(const SharedPtr\<System::IO::Stream\>\&, bool, bool) metodo

Crea un oggetto [Image](../) dal flusso specificato.

```cpp
static SharedPtr<Image> System::Drawing::Image::FromStream(const SharedPtr<System::IO::Stream> &stream, bool use_embedded_color_management=false, bool validate_image_data=1)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| stream | const [SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\>\& | Un flusso che contiene dati immagine |
| use_embedded_color_management | **bool** | IGNORED |
| validate_image_data | **bool** | IGNORED |

### Valore di ritorno

Un puntatore condiviso all'oggetto [Image](../) creato.

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [Image](../)
* Classe [Stream](../../../system.io/stream/)
* Spazio dei nomi [System::Drawing](../../)
* Libreria [Aspose.Slides](../../../)