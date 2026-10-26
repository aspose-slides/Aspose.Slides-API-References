---
title: is_only_document_properties_loaded property
second_title: Aspose.Slides für Python über .NET API-Referenz
description: 
type: docs
url: /de/aspose.slides/protectionmanager/is_only_document_properties_loaded/
weight: 90
---
## is_only_document_properties_loaded Eigenschaft
Diese Eigenschaft ist sinnvoll, wenn die Präsentationsdatei durch ein Passwort geschützt ist und die Dokumenteigenschaften dieser Datei öffentlich sind.
Der Wert true bedeutet, dass nur Dokumenteigenschaften aus einer verschlüsselten Präsentationsdatei ohne Verwendung eines Passworts geladen werden.
Der Wert false bedeutet, dass die gesamte verschlüsselte Präsentation mit dem richtigen Passwort geladen wird, nicht nur die Dokumenteigenschaften.
Wenn die Präsentation nicht verschlüsselt ist, ist der Eigenschaftswert immer false.
Wenn die Dokumenteigenschaften einer verschlüsselten Datei nicht öffentlich sind, ist der Eigenschaftswert immer false.
Wenn Presentation.EncryptDocumentProperties true ist, ist der Wert der Eigenschaft IsOnlyDocumentPropertiesLoaded immer false.
Nur lesbar **bool**.

### Definition:
```python
@property
def is_only_document_properties_loaded(self):
    ...
```

### Siehe auch
* Klasse [`ProtectionManager`](/slides/python-net/de/aspose.slides/protectionmanager)
* Modul [`aspose.slides`](/slides/python-net/de/aspose.slides)
* Bibliothek [`Aspose.Slides`](/slides/python-net)