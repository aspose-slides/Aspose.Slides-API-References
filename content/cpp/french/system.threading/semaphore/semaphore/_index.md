---
title: Semaphore()
second_title: Référence de l'API Aspose.Slides pour C++
description: Crée un sémaphore sans nom.
type: docs
weight: 1
url: /fr/system.threading/semaphore/semaphore/
---
## Semaphore::Semaphore(int, int) constructeur


Crée un sémaphore sans nom.

```cpp
System::Threading::Semaphore::Semaphore(int initialCount, int maximumCount)
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| initialCount | int | Nombre initial d'entrées actives. |
| maximumCount | int | Nombre maximal d'entrées autorisées. |

## Semaphore::Semaphore(int, int, const String\&) constructeur


Crée un sémaphore nommé.

```cpp
System::Threading::Semaphore::Semaphore(int initialCount, int maximumCount, const String &name)
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| initialCount | int | Nombre initial d'entrées actives. |
| maximumCount | int | Nombre maximal d'entrées autorisées. |
| name | const [String](../../../system/string/)\& | [Semaphore](../) nom. |

## Semaphore::Semaphore(int, int, const String\&, bool\&) constructeur


Crée un sémaphore nommé.

```cpp
System::Threading::Semaphore::Semaphore(int initialCount, int maximumCount, const String &name, bool &createdNew)
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| initialCount | int | Nombre initial d'entrées actives. |
| maximumCount | int | Nombre maximal d'entrées autorisées. |
| name | const [String](../../../system/string/)\& | [Semaphore](../) nom. |
| createdNew | **bool**\& | Référence à une variable qui est mise à true si le sémaphore a été créé et à false si un sémaphore existant portant le même nom a été réutilisé |

## Voir aussi

* Classe [Semaphore](../)
* Classe [String](../../../system/string/)
* Espace de noms [System::Threading](../../)
* Bibliothèque [Aspose.Slides](../../../)