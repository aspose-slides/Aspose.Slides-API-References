---
title: Marshal
second_title: Référence API Aspose.Slides pour C++
description: Fournit une implémentation du marshaling. Seulement pour la compatibilité avec le code traduit, car aucun code géré n'est pris en charge du côté C++. Il s'agit d'un type statique sans services d'instance. Vous ne devez jamais créer d'instances de celui-ci, quels que soient les moyens.
type: docs
weight: 14
url: /fr/system.runtime.interopservices/marshal/
---
## Classe Marshal

Fournit une implémentation du marshaling. Seulement pour la compatibilité avec le code traduit, car aucun code géré n'est supporté du côté C++. Il s'agit d'un type statique sans services d'instance. Vous ne devez jamais créer d'instances de ce type, quels que soient les moyens.

```cpp
class Marshal
```

## Méthodes

| Méthode | Description |
| --- | --- |
| static IntPtr [AllocHGlobal](./allochglobal/)(**int32_t**) | Alloue de la mémoire non gérée. |
| static IntPtr [AllocHGlobal](./allochglobal/)(IntPtr) | Alloue de la mémoire non gérée. |
| static void [Copy](./copy/)(const IntPtr, container\&&, int, int) | Implémente la sémantique de public static void Copy(IntPtr source, byte[] destination, int startIndex, int length). |
| static void [Copy](./copy/)(const void *, container\&&, int, int) | Implémente la sémantique de public static void Copy(IntPtr source, byte[] destination, int startIndex, int length). |
| static void [Copy](./copy/)(const container\&, int, void *, int) | Implémente la sémantique de public static void Copy(char[] source, int startIndex, IntPtr destination, int length). |
| static void [Copy](./copy/)(const container\&, int, IntPtr, int) | Implémente la sémantique de public static void Copy(char[] source, int startIndex, IntPtr destination, int length). |
| static void [FreeHGlobal](./freehglobal/)(IntPtr) | Libère la mémoire non gérée. |
| static TDelegate [GetDelegateForFunctionPointer](./getdelegateforfunctionpointer/)(IntPtr) | Convertit un pointeur de fonction non géré en un délégué d'un type spécifié. |
| static **int32_t** [GetHRForException](./gethrforexception/)(const [System::Exception](../../system/exception/)\&) | Obtient le HResult à partir d'une exception. |
| static [String](../../system/string/) [PtrToStringAnsi](./ptrtostringansi/)(IntPtr) | Crée un [String](../../system/string/) géré à partir d'une chaîne UTF8 terminée par zéro non gérée. |
| static [String](../../system/string/) [PtrToStringAnsi](./ptrtostringansi/)(IntPtr, int) | Crée un [String](../../system/string/) géré à partir d'une chaîne UTF8 non gérée. |
| static [String](../../system/string/) [PtrToStringAuto](./ptrtostringauto/)(IntPtr) | Crée un [String](../../system/string/) géré à partir d'une chaîne terminée par zéro non gérée. |
| static [String](../../system/string/) [PtrToStringAuto](./ptrtostringauto/)(IntPtr, int) | Crée un [String](../../system/string/) géré à partir d'une chaîne non gérée. |
| static [String](../../system/string/) [PtrToStringUni](./ptrtostringuni/)(IntPtr) | Crée un [String](../../system/string/) géré à partir d'une chaîne Unicode terminée par zéro non gérée. |
| static [String](../../system/string/) [PtrToStringUni](./ptrtostringuni/)(IntPtr, int) | Crée un [String](../../system/string/) géré à partir d'une chaîne Unicode non gérée. |
| static [String](../../system/string/) [PtrToStringUTF8](./ptrtostringutf8/)(IntPtr) | Crée un [String](../../system/string/) géré à partir d'une chaîne UTF8 terminée par zéro non gérée. |
| static [String](../../system/string/) [PtrToStringUTF8](./ptrtostringutf8/)(IntPtr, int) | Crée un [String](../../system/string/) géré à partir d'une chaîne UTF8 non gérée. |
| static **uint8_t** [ReadByte](./readbyte/)(IntPtr, int) | Lit un octet depuis la mémoire. |
| static **int16_t** [ReadInt16](./readint16/)(IntPtr, int) | Lit un entier court depuis la mémoire. |
| static **int32_t** [ReadInt32](./readint32/)(IntPtr, int) | Lit un entier depuis la mémoire. |
| static IntPtr [ReadIntPtr](./readintptr/)(IntPtr, int) | Lit un IntPtr depuis la mémoire. |
| static IntPtr [SecureStringToGlobalAllocAnsi](./securestringtoglobalallocansi/)(const [SharedPtr](../../system/sharedptr/)\<[Security::SecureString](../../system.security/securestring/)\>\&) | Copie le contenu de la chaîne sécurisée spécifiée dans la mémoire non gérée, en le convertissant au format ANSI. |
| static IntPtr [SecureStringToGlobalAllocUnicode](./securestringtoglobalallocunicode/)(const [SharedPtr](../../system/sharedptr/)\<[Security::SecureString](../../system.security/securestring/)\>\&) | Copie le contenu de la chaîne sécurisée spécifiée dans la mémoire non gérée. |
| static IntPtr [StringToHGlobalAnsi](./stringtohglobalansi/)(const [String](../../system/string/)\&) | Copie le contenu d'une chaîne spécifiée dans la mémoire non gérée. |
| static IntPtr [StringToHGlobalAuto](./stringtohglobalauto/)(const [String](../../system/string/)\&) | Copie le contenu d'une chaîne spécifiée dans la mémoire non gérée, en le convertissant au format ANSI si nécessaire. |
| static IntPtr [StringToHGlobalUni](./stringtohglobaluni/)(const [String](../../system/string/)\&) | Copie le contenu d'une chaîne spécifiée dans la mémoire non gérée. |
| static void [WriteByte](./writebyte/)(IntPtr, int, **uint8_t**) | Écrit un octet dans la mémoire. |
| static void [WriteByte](./writebyte/)(IntPtr, **uint8_t**) | Écrit un octet dans la mémoire. |
| static void [WriteInt16](./writeint16/)(IntPtr, int, **int16_t**) | Écrit un entier court dans la mémoire. |
| static void [WriteInt32](./writeint32/)(IntPtr, int, **int32_t**) | Écrit un entier dans la mémoire. |
| static void [WriteInt64](./writeint64/)(IntPtr, int, **int64_t**) | Écrit un entier long dans la mémoire. |
| static void [WriteIntPtr](./writeintptr/)(IntPtr, int, IntPtr) | Écrit un IntPtr dans la mémoire. |
| static void [ZeroFreeGlobalAllocAnsi](./zerofreeglobalallocansi/)(IntPtr) | Libère le pointeur de chaîne non gérée qui a été alloué avec la méthode SecureStringToGlobalAllocAnsi. |
| static void [ZeroFreeGlobalAllocUnicode](./zerofreeglobalallocunicode/)(IntPtr) | Libère le pointeur de chaîne non gérée qui a été alloué avec la méthode SecureStringToGlobalAllocUnicode. |

## Voir aussi

* Espace de noms [System::Runtime::InteropServices](../)
* Bibliothèque [Aspose.Slides](../../)