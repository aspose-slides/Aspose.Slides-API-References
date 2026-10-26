---
title: is_only_document_properties_loaded property
second_title: Aspose.Slides für Python über .NET API-Referenz
description: 
type: docs
url: /de/aspose.slides/iprotectionmanager/is_only_document_properties_loaded/
weight: 90
---
## is_only_document_properties_loaded Eigenschaft
Diese Eigenschaft ist sinnvoll, wenn die Präsentationsdatei passwortgeschützt ist und die Dokumenteigenschaften dieser Datei öffentlich sind.
Der Wert true bedeutet, dass nur die Dokumenteigenschaften aus einer verschlüsselten Präsentationsdatei ohne Verwendung eines Passworts geladen werden.
Der Wert false bedeutet, dass die gesamte verschlüsselte Präsentation mit dem richtigen Passwort geladen wird, nicht nur die Dokumenteigenschaften.
Wenn die Präsentation nicht verschlüsselt ist, ist der Eigenschaftswert stets false.
Wenn die Dokumenteigenschaften einer verschlüsselten Datei nicht öffentlich sind, ist der Eigenschaftswert stets false.
Wenn PresentationEx.EncryptDocumentProperties true ist, ist der Wert von IsOnlyDocumentPropertiesLoaded Eigenschaft stets false.
Nur lesbar **bool**.

### Definition:
```python
@property
def is_only_document_properties_loaded(self):
    ...
```

### Siehe auch
* Klasse [`IProtectionManager`](/slides/python-net/de/aspose.slides/iprotectionmanager)
* Modul [`aspose.slides`](/slides/python-net/de/aspose.slides)
* Bibliothek [`Aspose.Slides`](/slides/python-net)