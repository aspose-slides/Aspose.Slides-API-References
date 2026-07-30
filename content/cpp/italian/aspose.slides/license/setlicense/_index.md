---
title: SetLicense()
second_title: Riferimento API di Aspose.Slides per C++
description: Licenza il componente.
type: docs
weight: 14
url: /it/aspose.slides/license/setlicense/
---
## License::SetLicense(System::String) metodo


Licenza il componente.

```cpp
void Aspose::Slides::License::SetLicense(System::String licenseName) override
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| licenseName | [System::String](../../../system/string/) | Può essere un nome file completo o abbreviato o il nome di una risorsa incorporata. Usa una stringa vuota per passare alla modalità di valutazione. |
## Osservazioni



Cerca la licenza nelle seguenti posizioni:

1. Percorso esplicito.

2. La cartella dell'assembly del componente.

3. La cartella dell'assembly chiamante del client.

4. La cartella dell'assembly di ingresso.

5. Una risorsa incorporata nell'assembly chiamante del client.

**Nota:** su .NET Compact Framework, cerca la licenza solo in queste posizioni:

1. Percorso esplicito.

2. Una risorsa incorporata nell'assembly chiamante del client.

In questo esempio, verrà tentato di trovare un file di licenza denominato MyLicense.lic nella cartella che contiene il componente, nella cartella che contiene l'assembly chiamante, nella cartella dell'assembly di ingresso e poi nelle risorse incorporate dell'assembly chiamante. 
```cpp
auto license = MakeObject<License>();
license->SetLicense(u"MyLicense.lic");
```

## License::SetLicense(System::SharedPtr\<System::IO::Stream\>) metodo


Licenza il componente.

```cpp
void Aspose::Slides::License::SetLicense(System::SharedPtr<System::IO::Stream> stream) override
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Uno stream che contiene la licenza. |
## Osservazioni



Usa questo metodo per caricare una licenza da uno stream.


```cpp
auto license = MakeObject<License>();
license->SetLicense(myStream);
```

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [String](../../../system/string/)
* Classe [License](../)
* Classe [Stream](../../../system.io/stream/)
* Spazio dei nomi [Aspose::Slides](../../)
* Libreria [Aspose.Slides](../../../)