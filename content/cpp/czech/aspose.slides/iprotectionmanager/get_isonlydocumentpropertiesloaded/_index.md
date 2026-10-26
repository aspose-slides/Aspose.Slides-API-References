---
title: get_IsOnlyDocumentPropertiesLoaded()
second_title: Aspose.Slides pro C++ API Reference
description: Tato vlastnost má smysl, pokud je soubor prezentace chráněn heslem a vlastnosti dokumentu tohoto souboru jsou veřejné. Hodnota true znamená, že jsou z šifrovaného souboru prezentace načteny pouze vlastnosti dokumentu bez použití hesla. Hodnota false znamená, že je načtena celá šifrovaná prezentace s použitím správného hesla, nikoli pouze vlastnosti dokumentu. Pokud není prezentace šifrovaná, pak je hodnota vlastnosti vždy false. Pokud vlastnosti dokumentu šifrovaného souboru nejsou veřejné, pak je hodnota vlastnosti vždy false. Pokud je PresentationEx.EncryptDocumentProperties true, pak je hodnota vlastnosti IsOnlyDocumentPropertiesLoaded vždy false. Pouze pro čtení bool.
type: docs
weight: 40
url: /cs/aspose.slides/iprotectionmanager/get_isonlydocumentpropertiesloaded/
---
## IProtectionManager::get_IsOnlyDocumentPropertiesLoaded() metoda


Tato vlastnost má smysl, pokud je soubor prezentace chráněn heslem a vlastnosti dokumentu tohoto souboru jsou veřejné. Hodnota true znamená, že jsou z šifrovaného souboru prezentace načteny pouze vlastnosti dokumentu bez použití hesla. Hodnota false znamená, že je načtena celá šifrovaná prezentace s použitím správného hesla, nikoli pouze vlastnosti dokumentu. Pokud prezentace není šifrovaná, hodnota vlastnosti je vždy false. Pokud vlastnosti dokumentu šifrovaného souboru nejsou veřejné, hodnota vlastnosti je vždy false. Pokud je PresentationEx.EncryptDocumentProperties true, pak je hodnota vlastnosti IsOnlyDocumentPropertiesLoaded vždy false. Pouze pro čtení **bool**.

```cpp
virtual bool Aspose::Slides::IProtectionManager::get_IsOnlyDocumentPropertiesLoaded()=0
```

## Viz také

* Třída [IProtectionManager](../)
* Jmenný prostor [Aspose::Slides](../../)
* Knihovna [Aspose.Slides](../../../)