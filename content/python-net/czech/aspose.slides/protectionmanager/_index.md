---
title: ProtectionManager class
second_title: Aspose.Slides pro Python přes .NET API Reference
description: 
type: docs
url: /cs/aspose.slides/protectionmanager/
---
## ProtectionManager třída

Správa ochrany prezentace heslem.

Typ ProtectionManager vystavuje následující členy:

## Vlastnosti

| Vlastnost | Popis |
| :- | :- |
| [`encrypt_document_properties`](/slides/python-net/cs/aspose.slides/protectionmanager/encrypt_document_properties/) | Tato vlastnost dává smysl, pokud je prezentace chráněna heslem.<br/>            Pokud je true, pak jsou vlastnosti dokumentu v souboru prezentace šifrovány.<br/>            Pokud je false, pak jsou vlastnosti dokumentu veřejné, zatímco prezentace je šifrována.<br/>            Read/write **bool**. |
| [`is_encrypted`](/slides/python-net/cs/aspose.slides/protectionmanager/is_encrypted/) | Vrací hodnotu udávající, zda je tato instance šifrována.<br/>            Read-only **bool**. |
| [`is_only_document_properties_loaded`](/slides/python-net/cs/aspose.slides/protectionmanager/is_only_document_properties_loaded/) | Tato vlastnost dává smysl, pokud je soubor prezentace chráněn heslem a vlastnosti dokumentu tohoto souboru jsou veřejné.<br/>            Hodnota true znamená, že jsou načteny pouze vlastnosti dokumentu z šifrovaného souboru prezentace bez použití hesla.<br/>            Hodnota false znamená, že je načtena celá šifrovaná prezentace s použitím správného hesla, nikoli pouze vlastnosti dokumentu.<br/>            Pokud prezentace není šifrována, pak je hodnota vlastnosti vždy false.<br/>            Pokud vlastnosti dokumentu šifrovaného souboru nejsou veřejné, pak je hodnota vlastnosti vždy false.<br/>            Pokud je Presentation.EncryptDocumentProperties true, pak je hodnota vlastnosti IsOnlyDocumentPropertiesLoaded vždy false.<br/>            Read-only **bool**. |
| [`is_write_protected`](/slides/python-net/cs/aspose.slides/protectionmanager/is_write_protected/) | Vrací hodnotu udávající, zda je tato prezentace chráněna proti zápisu.<br/>            Read-only **bool**. |
| [`encryption_password`](/slides/python-net/cs/aspose.slides/protectionmanager/encryption_password/) | Vrací heslo používané pro šifrování prezentace.<br/>            Read-only **str**. |
| [`read_only_recommended`](/slides/python-net/cs/aspose.slides/protectionmanager/read_only_recommended/) | Vrací nebo nastavuje doporučení pouze pro čtení.<br/>            Read/write **bool**. |

## Metody

| Metoda | Popis |
| :- | :- |
| [`encrypt(self, encryption_password)`](/slides/python-net/cs/aspose.slides/protectionmanager/encrypt/#str) | Zašifruje prezentaci pomocí zadaného hesla. |
| [`remove_encryption(self)`](/slides/python-net/cs/aspose.slides/protectionmanager/remove_encryption/#) | Odstraní šifrování. |
| [`set_write_protection(self, password)`](/slides/python-net/cs/aspose.slides/protectionmanager/set_write_protection/#str) | Nastaví ochranu proti zápisu pro tuto prezentaci pomocí zadaného hesla. |
| [`remove_write_protection(self)`](/slides/python-net/cs/aspose.slides/protectionmanager/remove_write_protection/#) | Odstraní ochranu proti zápisu pro tuto prezentaci. |
| [`check_write_protection(self, password)`](/slides/python-net/cs/aspose.slides/protectionmanager/check_write_protection/#str) | Určuje, zda je prezentace chráněna heslem pro úpravy. |

### Viz také
* modul [`aspose.slides`](/slides/python-net/cs/aspose.slides)
* knihovna [`Aspose.Slides`](/slides/python-net)