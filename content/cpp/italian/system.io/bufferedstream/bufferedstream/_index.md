---
title: BufferedStream()
second_title: Riferimento API di Aspose.Slides per C++
description: Crea un oggetto BufferedStream che avvolge lo stream specificato e utilizza un buffer lungo 4096 byte.
type: docs
weight: 1
url: /it/system.io/bufferedstream/bufferedstream/
---
## BufferedStream::BufferedStream(const SharedPtr\<Stream\>\&) costruttore

Crea un oggetto [BufferedStream](../) che avvolge lo stream specificato e utilizza un buffer lungo 4096 byte.

```cpp
System::IO::BufferedStream::BufferedStream(const SharedPtr<Stream> &stream)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| stream | const [SharedPtr](../../../system/sharedptr/)\<[Stream](../../stream/)\>\& | L'oggetto [Stream](../../stream/) sottostante |

## BufferedStream::BufferedStream(const SharedPtr\<Stream\>\&, int) costruttore

Crea un oggetto [BufferedStream](../) che avvolge lo stream specificato e utilizza un buffer della dimensione specificata.

```cpp
System::IO::BufferedStream::BufferedStream(const SharedPtr<Stream> &stream, int bufferSize)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| stream | const [SharedPtr](../../../system/sharedptr/)\<[Stream](../../stream/)\>\& | L'oggetto [Stream](../../stream/) sottostante |
| bufferSize | int | La dimensione del buffer in byte |

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [Stream](../../stream/)
* Classe [BufferedStream](../)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)