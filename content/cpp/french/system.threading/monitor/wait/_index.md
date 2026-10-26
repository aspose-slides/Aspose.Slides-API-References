---
title: Wait()
second_title: Référence de l'API Aspose.Slides pour C++
description: Libère le verrou sur un objet et bloque le thread actuel jusqu'à ce qu'il reacquière le verrou. Si l'intervalle d'attente spécifié expire, le thread rejoint la file d'attente prête. Optionnellement, sort du domaine de synchronisation pour le contexte synchronisé avant l'attente et réacquiert le domaine après. Non implémenté.
type: docs
weight: 53
url: /fr/system.threading/monitor/wait/
---
## Monitor::Wait(const SharedPtr\<Object\>\&, int32_t, bool) méthode

Libère le verrou sur un objet et bloque le thread actuel jusqu'à ce qu'il reacquière le verrou. Si l'intervalle d'attente spécifié expire, le thread rejoint la file d'attente prête. Optionnellement, sort du domaine de synchronisation pour le contexte synchronisé avant l'attente et réacquiert le domaine après. Non implémenté.

```cpp
static bool System::Threading::Monitor::Wait(const SharedPtr<Object> &obj, int32_t millisecondsTimeout, bool exitContext)
```
## Monitor::Wait(const SharedPtr\<Object\>\&, TimeSpan, bool) méthode

Libère le verrou sur un objet et bloque le thread actuel jusqu'à ce qu'il reacquière le verrou. Si l'intervalle d'attente spécifié expire, le thread rejoint la file d'attente prête. Optionnellement, sort du domaine de synchronisation pour le contexte synchronisé avant l'attente et réacquiert le domaine après. Non implémenté.

```cpp
static bool System::Threading::Monitor::Wait(const SharedPtr<Object> &obj, TimeSpan timeout, bool exitContext)
```
## Monitor::Wait(const SharedPtr\<Object\>\&, int32_t) méthode

Libère le verrou sur un objet et bloque le thread actuel jusqu'à ce qu'il reacquière le verrou. Si l'intervalle d'attente spécifié expire, le thread rejoint la file d'attente prête. Non implémenté.

```cpp
static bool System::Threading::Monitor::Wait(const SharedPtr<Object> &obj, int32_t millisecondsTimeout)
```
## Monitor::Wait(const SharedPtr\<Object\>\&, TimeSpan) méthode

Libère le verrou sur un objet et bloque le thread actuel jusqu'à ce qu'il reacquière le verrou. Si l'intervalle d'attente spécifié expire, le thread rejoint la file d'attente prête. Non implémenté.

```cpp
static bool System::Threading::Monitor::Wait(const SharedPtr<Object> &obj, TimeSpan timeout)
```
## Monitor::Wait(const SharedPtr\<Object\>\&) méthode

Libère le verrou sur un objet et bloque le thread actuel jusqu'à ce qu'il reacquière le verrou Non implémenté.

```cpp
static bool System::Threading::Monitor::Wait(const SharedPtr<Object> &obj)
```
## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [Object](../../../system/object/)
* Classe [Monitor](../)
* Classe [TimeSpan](../../../system/timespan/)
* Espace de noms [System::Threading](../../)
* Bibliothèque [Aspose.Slides](../../../)