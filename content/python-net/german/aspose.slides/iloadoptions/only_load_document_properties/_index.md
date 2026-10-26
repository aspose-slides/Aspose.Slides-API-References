---
title: only_load_document_properties property
second_title: Aspose.Slides für Python via .NET API-Referenz
description: 
type: docs
url: /de/aspose.slides/iloadoptions/only_load_document_properties/
weight: 100
---
## only_load_document_properties Eigenschaft
Diese Eigenschaft ist sinnvoll, wenn die Präsentationsdatei passwortgeschützt ist.
            Der Wert true bedeutet, dass nur Dokumenteigenschaften aus einer verschlüsselten 
            Präsentationsdatei geladen werden müssen und das Passwort ignoriert wird.
            Der Wert false bedeutet, dass die gesamte verschlüsselte Präsentation mit dem richtigen 
            Passwort geladen werden muss.
            Wenn die Präsentation nicht verschlüsselt ist, wird der Eigenschaftswert immer ignoriert.
            Wenn die Dokumenteigenschaften einer verschlüsselten Datei nicht öffentlich sind und der 
            Eigenschaftswert true ist, können die Dokumenteigenschaften nicht geladen werden und es wird 
            eine Ausnahme ausgelöst.
            Lese-schreiben **bool**.

### Definition:
```python
@property
def only_load_document_properties(self):
    ...

@only_load_document_properties.setter
def only_load_document_properties(self, value):
    ...
```


### Siehe auch
* Klasse [`ILoadOptions`](/slides/python-net/de/aspose.slides/iloadoptions)
* Modul [`aspose.slides`](/slides/python-net/de/aspose.slides)
* Bibliothek [`Aspose.Slides`](/slides/python-net)