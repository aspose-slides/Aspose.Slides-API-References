---
title: AudioCollection
type: docs
weight: 0
url: /php-java/audiocollection/
---

# AudioCollection class

 Represents a collection of embedded audio files.
 

## Methods

| name | return type | description |
| --- | --- | --- |
| [addAudio](/slides/php-java/audiocollection/addaudio/)(IAudio) | IAudio | Adds a copy of an audio file from an another presentation. |
| [addAudio](/slides/php-java/audiocollection/addaudio/)(InputStream) | IAudio | Creates and adds a audio to a presentation from stream. |
| [addAudio](/slides/php-java/audiocollection/addaudio/)(InputStream, int) | IAudio | Creates and adds a audio to a presentation from stream. |
| [addAudio](/slides/php-java/audiocollection/addaudio/)(byte[]) | IAudio | Creates and adds a audio to a presentation from byte array. |
| [getSyncRoot](/slides/php-java/audiocollection/getsyncroot/)() | Object | Returns a synchronization root. Read-only Object. |
| [get_Item](/slides/php-java/audiocollection/get_item/)(int) | IAudio | Gets the element at the specified index. Read-only IAudio. |
| [isSynchronized](/slides/php-java/audiocollection/issynchronized/)() | boolean | Returns a value indicating whether access to the collection is synchronized (thread-safe). Read-only boolean. |
| [iterator](/slides/php-java/audiocollection/iterator/)() | IGenericEnumerator | Returns an enumerator that iterates through the collection. |
| [iteratorJava](/slides/php-java/audiocollection/iteratorjava/)() | IGenericEnumerator | Returns a java iterator for the entire collection. |
| [size](/slides/php-java/audiocollection/size/)() | int | Returns a number of audio files in the collection. Read-only int. |
