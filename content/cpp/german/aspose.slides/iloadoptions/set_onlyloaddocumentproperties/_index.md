---
title: set_OnlyLoadDocumentProperties()
second_title: Aspose.Slides für C++ API-Referenz
description: Diese Eigenschaft ist sinnvoll, wenn die Präsentationsdatei passwortgeschützt ist. Der Wert true bedeutet, dass nur Dokumenteigenschaften aus einer verschlüsselten Präsentationsdatei geladen werden müssen und das Passwort ignoriert wird. Der Wert false bedeutet, dass die gesamte verschlüsselte Präsentation mit dem richtigen Passwort geladen werden muss. Ist die Präsentation nicht verschlüsselt, wird der Eigenschaftswert immer ignoriert. Sind die Dokumenteigenschaften einer verschlüsselten Datei nicht öffentlich und der Eigenschaftswert ist true, können die Dokumenteigenschaften nicht geladen werden und es wird eine Ausnahme ausgelöst. Schreibt bool.
type: docs
weight: 144
url: /de/aspose.slides/iloadoptions/set_onlyloaddocumentproperties/
---
## ILoadOptions::set_OnlyLoadDocumentProperties(bool) Methode

Diese Eigenschaft ist sinnvoll, wenn die Präsentationsdatei durch ein Passwort geschützt ist. Der Wert true bedeutet, dass nur Dokumenteigenschaften aus einer verschlüsselten Präsentationsdatei geladen werden sollen und das Passwort ignoriert wird. Der Wert false bedeutet, dass die gesamte verschlüsselte Präsentation mit dem richtigen Passwort geladen werden muss. Ist die Präsentation nicht verschlüsselt, wird der Eigenschaftswert stets ignoriert. Sind die Dokumenteigenschaften einer verschlüsselten Datei nicht öffentlich und ist der Eigenschaftswert true, können die Dokumenteigenschaften nicht geladen werden und es wird eine Ausnahme ausgelöst. Schreibt **bool**.

```cpp
virtual void Aspose::Slides::ILoadOptions::set_OnlyLoadDocumentProperties(bool value)=0
```

## Siehe auch

* Klasse [ILoadOptions](../)
* Namensraum [Aspose::Slides](../../)
* Bibliothek [Aspose.Slides](../../../)