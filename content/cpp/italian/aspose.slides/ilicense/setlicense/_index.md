---
title: SetLicense()
second_title: Riferimento API di Aspose.Slides per C++
description: Concede una licenza al componente.
type: docs
weight: 1
url: /it/aspose.slides/ilicense/setlicense/
---
## ILicense::SetLicense(System::String) metodo

Concede una licenza al componente.

```cpp
virtual void Aspose::Slides::ILicense::SetLicense(System::String licenseName)=0
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| licenseName | [System::String](../../../system/string/) | Può essere un nome file completo o breve o il nome di una risorsa incorporata. Usa una stringa vuota per passare alla modalità di valutazione. |

## Osservazioni

Cerca di trovare la licenza nei seguenti percorsi:

1. Percorso esplicito.
2. La cartella dell'assembly del componente.
3. La cartella dell'assembly chiamante del client.
4. La cartella dell'assembly di ingresso.
5. Una risorsa incorporata nell'assembly chiamante del client.

**Nota:**Su .NET Compact Framework, cerca di trovare la licenza solo in queste posizioni:

1. Percorso esplicito.
2. Una risorsa incorporata nell'assembly chiamante del client.

In questo esempio, verrà tentato di trovare un file di licenza chiamato MyLicense.lic nella cartella che contiene il componente, nella cartella che contiene l'assembly chiamante, nella cartella dell'assembly di ingresso e poi nelle risorse incorporate dell'assembly chiamante. 
```cpp
auto license = MakeObject<License>();
license->SetLicense(u"MyLicense.lic");
```

## ILicense::SetLicense(System::SharedPtr\<System::IO::Stream\>) metodo

Concede una licenza al componente.

```cpp
virtual void Aspose::Slides::ILicense::SetLicense(System::SharedPtr<System::IO::Stream> stream)=0
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Un flusso che contiene la licenza. |

## Osservazioni

Usa questo metodo per caricare una licenza da uno stream.

```cpp
auto license = MakeObject<License>();
license->SetLicense(myStream);
```

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [String](../../../system/string/)
* Classe [ILicense](../)
* Classe [Stream](../../../system.io/stream/)
* Spazio dei nomi [Aspose::Slides](../../)
* Libreria [Aspose.Slides](../../../)