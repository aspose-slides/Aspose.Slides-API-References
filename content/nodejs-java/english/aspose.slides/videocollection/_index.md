---
title: VideoCollection
second_title: Aspose.Sildes for Node.js via Java API Reference
description: 
type: docs

url: /aspose.slides/videocollection/
---

## VideoCollection class

 Represents a collection of Video objects.
 
| [addVideo] ([Video]) | Adds a copy of an video file from an another presentation. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| video | [Video] | Source video. |

### Result
[Video]


---


| [addVideoFromStream ] (VideoCollection, [ReadStream], Function) | Creates and adds a video to a presentation from stream. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| videocollection | VideoCollection  | link to self |
| stream | [ReadStream] | Stream to add video file from. |
| callback | Function | callback(error, result) - Callback to be called when the method has completed |

### Result
[Video]


---


| [addVideoFromStream ] (VideoCollection, [ReadStream], [int], Function) | Creates and adds a video to a presentation from stream. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| videocollection | VideoCollection  | link to self |
| stream | [ReadStream] | Stream to add video file from. |
| loadingStreamBehavior | [int] | The behavior which will be applied to the stream. |
| callback | Function | callback(error, result) - Callback to be called when the method has completed |

### Result
[Video]


---


| [addVideo] ([byte[]]) | Creates and adds a video to a presentation from byte array. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| videoData | [byte[]] | Video bytes. |

### Result
[Video]


---


| [getSyncRoot] () | Returns a synchronization root. Read-only Object. |

### Result
Object


---


| [get_Item] ([int]) | Gets the element at the specified index. Read-only IVideo. |

### Result
[Video]


---


| [isSynchronized] () | Returns a value indicating whether access to the collection is synchronized (thread-safe). Read-only boolean. |

### Result
boolean


---


| [iterator] () | Returns an enumerator that iterates through the collection. |

### Result



---


| [iteratorJava] () | Returns a java iterator for the entire collection. |

### Result



---


| [size] () | Returns a number of video files in the collection. Read-only int. |

### Result
int


---


