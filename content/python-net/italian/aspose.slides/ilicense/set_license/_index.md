---
title: set_license method
second_title: Aspose.Slides per Python tramite .NET API Reference
description: 
type: docs
url: /it/aspose.slides/ilicense/set_license/
weight: 30
---
## set_license(self, license_name) {#str}
Concede la licenza al componente.


```python
def set_license(self, license_name):
    ...
```


| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| license_name | **str** | Può essere un nome file completo o abbreviato o il nome di una risorsa incorporata.<br/><br/>Utilizzare una stringa vuota per passare alla modalità di valutazione. |

### Osservazioni

Cerca la licenza nelle seguenti posizioni:


1. Percorso esplicito.


2. La cartella dell'assembly del componente.


3. La cartella dell'assembly chiamante del client.


4. La cartella dell'assembly di ingresso.


5. Una risorsa incorporata nell'assembly chiamante del client.


**Nota:** Con .NET Compact Framework, cerca la licenza solo in queste posizioni:


1. Percorso esplicito.


2. Una risorsa incorporata nell'assembly chiamante del client.


## set_license(self, stream) {#iorawiobase}
Concede la licenza al componente.


```python
def set_license(self, stream):
    ...
```


| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| stream | **io.RawIOBase** | Un flusso che contiene la licenza. |

### Osservazioni

Utilizzare questo metodo per caricare una licenza da un flusso.



### Vedi anche
* classe [`ILicense`](/slides/python-net/it/aspose.slides/ilicense)
* modulo [`aspose.slides`](/slides/python-net/it/aspose.slides)
* libreria [`Aspose.Slides`](/slides/python-net)