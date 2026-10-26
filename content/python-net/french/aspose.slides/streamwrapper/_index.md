---
title: StreamWrapper class
second_title: Référence API Aspose.Slides pour Python via .NET
description: 
type: docs
url: /fr/aspose.slides/streamwrapper/
---
## StreamWrapper classe

Wrapper Aspose.IO.Stream pour l’interface COM.

Le type StreamWrapper expose les membres suivants :

## Propriétés

| Propriété | Description |
| :- | :- |
| [`stream`](/slides/python-net/fr/aspose.slides/streamwrapper/stream/) | Obtient un flux.<br/>            Lecture seule **io.RawIOBase**. |
| [`can_read`](/slides/python-net/fr/aspose.slides/streamwrapper/can_read/) | Obtient une valeur indiquant si le flux actuel prend en charge la lecture.<br/>            Lecture seule **bool**. |
| [`can_seek`](/slides/python-net/fr/aspose.slides/streamwrapper/can_seek/) | Obtient une valeur indiquant si le flux actuel prend en charge le déplacement.<br/>            Lecture seule **bool**. |
| [`can_write`](/slides/python-net/fr/aspose.slides/streamwrapper/can_write/) | Obtient une valeur indiquant si le flux actuel prend en charge l’écriture.<br/>            Lecture seule **bool**. |
| [`length`](/slides/python-net/fr/aspose.slides/streamwrapper/length/) | Obtient la longueur en octets du flux.<br/>            Lecture seule **int**. |
| [`position`](/slides/python-net/fr/aspose.slides/streamwrapper/position/) | Obtient ou définit la position dans le flux actuel.<br/>            Lecture seule **int**. |

## Méthodes

| Méthode | Description |
| :- | :- |
| [`close(self)`](/slides/python-net/fr/aspose.slides/streamwrapper/close/#) | Ferme le flux actuel et libère toutes les ressources. |
| [`flush(self)`](/slides/python-net/fr/aspose.slides/streamwrapper/flush/#) | Efface tous les tampons de ce flux et force l’écriture des données mises en mémoire tampon sur le dispositif sous-jacent. |
| [`read(self, buffer, offset, count)`](/slides/python-net/fr/aspose.slides/streamwrapper/read/#bytes-int-int) | Lit une séquence d’octets du flux actuel et avance la position dans le flux du nombre d’octets lus. |
| [`read_byte(self)`](/slides/python-net/fr/aspose.slides/streamwrapper/read_byte/#) | Lit un octet du flux et avance la position dans le flux d’un octet, ou renvoie -1 si la fin du flux est atteinte. |
| [`seek(self, offset, origin)`](/slides/python-net/fr/aspose.slides/streamwrapper/seek/#int-systemioseekorigin) | Définit la position dans le flux actuel |
| [`write(self, buffer, offset, count)`](/slides/python-net/fr/aspose.slides/streamwrapper/write/#bytes-int-int) | Écrit une séquence d’octets dans le flux actuel et avance la position actuelle dans ce flux du nombre d’octets écrits. |
| [`write_byte(self, value)`](/slides/python-net/fr/aspose.slides/streamwrapper/write_byte/#int) | Écrit un octet à la position actuelle du flux et avance la position dans le flux d’un octet. |

### Voir aussi
* module [`aspose.slides`](/slides/python-net/fr/aspose.slides)
* bibliothèque [`Aspose.Slides`](/slides/python-net)