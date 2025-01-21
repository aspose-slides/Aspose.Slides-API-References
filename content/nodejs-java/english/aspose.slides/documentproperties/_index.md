---
title: DocumentProperties
second_title: Aspose.Sildes for Node.js via Java API Reference
description: 
type: docs

url: /aspose.slides/documentproperties/
---

## DocumentProperties class

 Represents properties of a presentation.
 
### DocumentProperties {#DocumentProperties}

| Name | Description |
| --- | --- |
| DocumentProperties() | Initializes new instance of class DocumentProperties. |

 **Returns:**
DocumentProperties


---


### clearBuiltInProperties {#clearBuiltInProperties}

| Name | Description |
| --- | --- |
| clearBuiltInProperties () | Clears and sets default values for all builtIn properties. |


---


### clearCustomProperties {#clearCustomProperties}

| Name | Description |
| --- | --- |
| clearCustomProperties () | Removes all custom properties. |


---


### cloneT {#cloneT}

| Name | Description |
| --- | --- |
| cloneT () | Clones current object |

 **Returns:**
[DocumentProperties](../documentproperties)


---


### containsCustomProperty {#containsCustomProperty}

| Name | Description |
| --- | --- |
| containsCustomProperty (String) | Check presents of a custom property with a specified name. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| name | String | Name of a custom property to check. |

 **Returns:**
boolean


---


### deepClone {#deepClone}

| Name | Description |
| --- | --- |
| deepClone () | Clones current object |

 **Returns:**
Object


---


### getAppVersion {#getAppVersion}

| Name | Description |
| --- | --- |
| getAppVersion () | Returns the app version. Read-only String. |

 **Returns:**
String


---


### getApplicationTemplate {#getApplicationTemplate}

| Name | Description |
| --- | --- |
| getApplicationTemplate () | Returns or sets the template of a application. Read/write String. |

 **Returns:**
String


---


### getAuthor {#getAuthor}

| Name | Description |
| --- | --- |
| getAuthor () | Returns or sets the author of a presentation. Read/write String. |

 **Returns:**
String


---


### getCategory {#getCategory}

| Name | Description |
| --- | --- |
| getCategory () | Returns or sets the category of a presentation. Read/write String. |

 **Returns:**
String


---


### getComments {#getComments}

| Name | Description |
| --- | --- |
| getComments () | Returns or sets the comments of a presentation. Read/write String. |

 **Returns:**
String


---


### getCompany {#getCompany}

| Name | Description |
| --- | --- |
| getCompany () | Returns or sets the company property. Read/write String. |

 **Returns:**
String


---


### getContentStatus {#getContentStatus}

| Name | Description |
| --- | --- |
| getContentStatus () | Returns or sets the content status of a presentation. Read/write String. |

 **Returns:**
String


---


### getContentType {#getContentType}

| Name | Description |
| --- | --- |
| getContentType () | Returns or sets the content type of a presentation. Read/write String. |

 **Returns:**
String


---


### getCountOfCustomProperties {#getCountOfCustomProperties}

| Name | Description |
| --- | --- |
| getCountOfCustomProperties () | Returns the number of custom properties actually contained in a collection. Read-only int. |

 **Returns:**
int


---


### getCreatedTime {#getCreatedTime}

| Name | Description |
| --- | --- |
| getCreatedTime () | Returns the date a presentation was created. Values are in UTC. Read/write java.util.Date. |

 **Returns:**
Date


---


### getCustomPropertyName {#getCustomPropertyName}

| Name | Description |
| --- | --- |
| getCustomPropertyName (int) | Return a custom property name at the specified index. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| index | int | The zero-based index of a custom property to get. |

 **Returns:**
String

 **Error**

| Error | Condition |
| --- | --- |
 | ArgumentOutOfRangeException | Index is less than zero. Index is equal to or greater than Count. |


---


### getCustomPropertyValue {#getCustomPropertyValue}

| Name | Description |
| --- | --- |
| getCustomPropertyValue (String, boolean[]) | Gets a named boolean value from the custom properties. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| name | String | Name of the custom property to get |
| value | boolean[] | Custom property value |


---


### getCustomPropertyValue {#getCustomPropertyValue}

| Name | Description |
| --- | --- |
| getCustomPropertyValue (String, int[]) | Gets a named integer value from the custom properties. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| name | String | Name of the custom property to get |
| value | int[] | Custom property value |


---


### getCustomPropertyValue {#getCustomPropertyValue}

| Name | Description |
| --- | --- |
| getCustomPropertyValue (String, java.util.Date[]) | Gets a named DateTime value from the custom properties. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| name | String | Name of the custom property to get |
| value | java.util.Date[] | Custom property value |


---


### getCustomPropertyValue {#getCustomPropertyValue}

| Name | Description |
| --- | --- |
| getCustomPropertyValue (String, java.lang.String[]) | Gets a named string value from the custom properties. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| name | String | Name of the custom property to get |
| value | java.lang.String[] | Custom property value |


---


### getCustomPropertyValue {#getCustomPropertyValue}

| Name | Description |
| --- | --- |
| getCustomPropertyValue (String, float[]) | Gets a named float value from the custom properties. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| name | String | Name of the custom property to get |
| value | float[] | Custom property value |


---


### getCustomPropertyValue {#getCustomPropertyValue}

| Name | Description |
| --- | --- |
| getCustomPropertyValue (String, double[]) | Gets a named double value from the custom properties. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| name | String | Name of the custom property to get. |
| value | double[] | Custom property value |


---


### getHeadingPairs {#getHeadingPairs}

| Name | Description |
| --- | --- |
| getHeadingPairs () | Indicates the grouping of document parts and the number of parts in each group. Read-only IHeadingPair[]. |

 **Returns:**
[HeadingPair](../headingpair)


---


### getHiddenSlides {#getHiddenSlides}

| Name | Description |
| --- | --- |
| getHiddenSlides () | Returns the number of hidden slides in a presentation document. Read-only int. |

 **Returns:**
int


---


### getHyperlinkBase {#getHyperlinkBase}

| Name | Description |
| --- | --- |
| getHyperlinkBase () | Returns or sets the HyperlinkBase document property. Read/write String. |

 **Returns:**
String


---


### getHyperlinksChanged {#getHyperlinksChanged}

| Name | Description |
| --- | --- |
| getHyperlinksChanged () | Specifies that one or more hyperlinks in this part were updated exclusively in this part by a producer. The next producer to open this document shall update the hyperlink relationships with the new hyperlinks specified in this part. Read/write boolean. |

 **Returns:**
boolean


---


### getKeywords {#getKeywords}

| Name | Description |
| --- | --- |
| getKeywords () | Returns or sets the keywords of a presentation. Read/write String. |

 **Returns:**
String


---


### getLastPrinted {#getLastPrinted}

| Name | Description |
| --- | --- |
| getLastPrinted () | Returns the date when a presentation was printed last time. Read/write java.util.Date. |

 **Returns:**
Date


---


### getLastSavedBy {#getLastSavedBy}

| Name | Description |
| --- | --- |
| getLastSavedBy () | Returns or sets the name of a last person who modified a presentation. Read/write String. |

 **Returns:**
String


---


### getLastSavedTime {#getLastSavedTime}

| Name | Description |
| --- | --- |
| getLastSavedTime () | Returns the date a presentation was last modified. Values are in UTC. Read-only in case of Presentation.DocumentProperties (because it will be updated internally while IPresentation object saving process). Can be changed via DocumentProperties instance returning by function IPresentationInfo#readDocumentProperties Please see the example in IPresentationInfo#updateDocumentProperties(IDocumentProperties) function summary. |

 **Returns:**
Date


---


### getLinksUpToDate {#getLinksUpToDate}

| Name | Description |
| --- | --- |
| getLinksUpToDate () | Indicates whether hyperlinks in a document are up-to-date. Set this element to true to indicate that hyperlinks are updated. Set this element to false to indicate that hyperlinks are outdated. Read/write boolean. |

 **Returns:**
boolean


---


### getManager {#getManager}

| Name | Description |
| --- | --- |
| getManager () | Returns or sets the manager property. Read/write String. |

 **Returns:**
String


---


### getMultimediaClips {#getMultimediaClips}

| Name | Description |
| --- | --- |
| getMultimediaClips () | Returns the total number of sound or video clips that are present in the document. Read-only int. |

 **Returns:**
int


---


### getNameOfApplication {#getNameOfApplication}

| Name | Description |
| --- | --- |
| getNameOfApplication () | Returns or sets the name of the application. Read/write String. |

 **Returns:**
String


---


### getNotes {#getNotes}

| Name | Description |
| --- | --- |
| getNotes () | Returns the number of slides in a presentation containing notes. Read-only int. |

 **Returns:**
int


---


### getParagraphs {#getParagraphs}

| Name | Description |
| --- | --- |
| getParagraphs () | Returns the total number of paragraphs found in a document if applicable. Read-only int. |

 **Returns:**
int


---


### getPresentationFormat {#getPresentationFormat}

| Name | Description |
| --- | --- |
| getPresentationFormat () | Returns or sets the intended format of a presentation. Read/write String. |

 **Returns:**
String


---


### getRevisionNumber {#getRevisionNumber}

| Name | Description |
| --- | --- |
| getRevisionNumber () | Returns or sets the presentation revision number. Read/write int. |

 **Returns:**
int


---


### getScaleCrop {#getScaleCrop}

| Name | Description |
| --- | --- |
| getScaleCrop () | Indicates the display mode of the document thumbnail. Set this element to true to enable scaling of the document thumbnail to the display. Set this element to false to enable cropping of the document thumbnail to show only sections that fits the display. Read/write boolean. |

 **Returns:**
boolean


---


### getSharedDoc {#getSharedDoc}

| Name | Description |
| --- | --- |
| getSharedDoc () | Determines whether the presentation is shared between multiple people. Read/write boolean. |

 **Returns:**
boolean


---


### getSlides {#getSlides}

| Name | Description |
| --- | --- |
| getSlides () | Returns the total number of slides in a presentation document. Read-only int. |

 **Returns:**
int


---


### getSubject {#getSubject}

| Name | Description |
| --- | --- |
| getSubject () | Returns or sets the subject of a presentation. Read/write String. |

 **Returns:**
String


---


### getTitle {#getTitle}

| Name | Description |
| --- | --- |
| getTitle () | Returns or sets the title of a presentation. Read/write String. |

 **Returns:**
String


---


### getTitlesOfParts {#getTitlesOfParts}

| Name | Description |
| --- | --- |
| getTitlesOfParts () | Specifies the title of each document part. These parts are not document parts but conceptual representations of document sections. Read-only int. |

 **Returns:**
String


---


### getTotalEditingTime {#getTotalEditingTime}

| Name | Description |
| --- | --- |
| getTotalEditingTime () | Total editing time of a presentation. Read/write double. |

 **Returns:**
double


---


### getWords {#getWords}

| Name | Description |
| --- | --- |
| getWords () | Returns the total number of words contained in a document. Read-only int. |

 **Returns:**
int


---


### get_Item {#get_Item}

| Name | Description |
| --- | --- |
| get_Item (String) | Returns or sets the custom property associated with a specified name. Read/write Object. Value can be int, float, String, boolean or Date. |

 **Returns:**
Object


---


### removeCustomProperty {#removeCustomProperty}

| Name | Description |
| --- | --- |
| removeCustomProperty (String) | Remove a custom property associated with a specified name. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| name | String | Name of a custom property to remove. |

 **Returns:**
boolean


---


### setApplicationTemplate {#setApplicationTemplate}

| Name | Description |
| --- | --- |
| setApplicationTemplate (String) | Returns or sets the template of a application. Read/write String. |


---


### setAuthor {#setAuthor}

| Name | Description |
| --- | --- |
| setAuthor (String) | Returns or sets the author of a presentation. Read/write String. |


---


### setCategory {#setCategory}

| Name | Description |
| --- | --- |
| setCategory (String) | Returns or sets the category of a presentation. Read/write String. |


---


### setComments {#setComments}

| Name | Description |
| --- | --- |
| setComments (String) | Returns or sets the comments of a presentation. Read/write String. |


---


### setCompany {#setCompany}

| Name | Description |
| --- | --- |
| setCompany (String) | Returns or sets the company property. Read/write String. |


---


### setContentStatus {#setContentStatus}

| Name | Description |
| --- | --- |
| setContentStatus (String) | Returns or sets the content status of a presentation. Read/write String. |


---


### setContentType {#setContentType}

| Name | Description |
| --- | --- |
| setContentType (String) | Returns or sets the content type of a presentation. Read/write String. |


---


### setCreatedTime {#setCreatedTime}

| Name | Description |
| --- | --- |
| setCreatedTime (Date) | Returns the date a presentation was created. Values are in UTC. Read/write java.util.Date. |


---


### setCustomPropertyValue {#setCustomPropertyValue}

| Name | Description |
| --- | --- |
| setCustomPropertyValue (String, boolean) | Sets a named boolean custom property. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| name | String | Name of the custom property to set |
| value | boolean | Custom property value |


---


### setCustomPropertyValue {#setCustomPropertyValue}

| Name | Description |
| --- | --- |
| setCustomPropertyValue (String, int) | Sets a named integer custom property. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| name | String | Name of the custom property to set |
| value | int | Custom property value |


---


### setCustomPropertyValue {#setCustomPropertyValue}

| Name | Description |
| --- | --- |
| setCustomPropertyValue (String, Date) | Sets a named DateTime custom property. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| name | String | Name of the custom property to set |
| value | Date | Custom property value |


---


### setCustomPropertyValue {#setCustomPropertyValue}

| Name | Description |
| --- | --- |
| setCustomPropertyValue (String, String) | Sets a named string custom property. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| name | String | Name of the custom property to set |
| value | String | Custom property value |


---


### setCustomPropertyValue {#setCustomPropertyValue}

| Name | Description |
| --- | --- |
| setCustomPropertyValue (String, float) | Sets a named float custom property. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| name | String | Name of the custom property to set |
| value | float | Custom property value |


---


### setCustomPropertyValue {#setCustomPropertyValue}

| Name | Description |
| --- | --- |
| setCustomPropertyValue (String, double) | Sets a named double custom property. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| name | String | Name of the custom property to set |
| value | double | Custom property value |


---


### setHyperlinkBase {#setHyperlinkBase}

| Name | Description |
| --- | --- |
| setHyperlinkBase (String) | Returns or sets the HyperlinkBase document property. Read/write String. |


---


### setHyperlinksChanged {#setHyperlinksChanged}

| Name | Description |
| --- | --- |
| setHyperlinksChanged (boolean) | Specifies that one or more hyperlinks in this part were updated exclusively in this part by a producer. The next producer to open this document shall update the hyperlink relationships with the new hyperlinks specified in this part. Read/write boolean. |


---


### setKeywords {#setKeywords}

| Name | Description |
| --- | --- |
| setKeywords (String) | Returns or sets the keywords of a presentation. Read/write String. |


---


### setLastPrinted {#setLastPrinted}

| Name | Description |
| --- | --- |
| setLastPrinted (Date) | Returns the date when a presentation was printed last time. Read/write java.util.Date. |


---


### setLastSavedBy {#setLastSavedBy}

| Name | Description |
| --- | --- |
| setLastSavedBy (String) | Returns or sets the name of a last person who modified a presentation. Read/write String. |


---


### setLastSavedTime {#setLastSavedTime}

| Name | Description |
| --- | --- |
| setLastSavedTime (Date) | Returns the date a presentation was last modified. Values are in UTC. Read-only in case of Presentation.DocumentProperties (because it will be updated internally while IPresentation object saving process). Can be changed via DocumentProperties instance returning by function IPresentationInfo#readDocumentProperties Please see the example in IPresentationInfo#updateDocumentProperties(IDocumentProperties) function summary. |


---


### setLinksUpToDate {#setLinksUpToDate}

| Name | Description |
| --- | --- |
| setLinksUpToDate (boolean) | Indicates whether hyperlinks in a document are up-to-date. Set this element to true to indicate that hyperlinks are updated. Set this element to false to indicate that hyperlinks are outdated. Read/write boolean. |


---


### setManager {#setManager}

| Name | Description |
| --- | --- |
| setManager (String) | Returns or sets the manager property. Read/write String. |


---


### setNameOfApplication {#setNameOfApplication}

| Name | Description |
| --- | --- |
| setNameOfApplication (String) | Returns or sets the name of the application. Read/write String. |


---


### setPresentationFormat {#setPresentationFormat}

| Name | Description |
| --- | --- |
| setPresentationFormat (String) | Returns or sets the intended format of a presentation. Read/write String. |


---


### setRevisionNumber {#setRevisionNumber}

| Name | Description |
| --- | --- |
| setRevisionNumber (int) | Returns or sets the presentation revision number. Read/write int. |


---


### setScaleCrop {#setScaleCrop}

| Name | Description |
| --- | --- |
| setScaleCrop (boolean) | Indicates the display mode of the document thumbnail. Set this element to true to enable scaling of the document thumbnail to the display. Set this element to false to enable cropping of the document thumbnail to show only sections that fits the display. Read/write boolean. |


---


### setSharedDoc {#setSharedDoc}

| Name | Description |
| --- | --- |
| setSharedDoc (boolean) | Determines whether the presentation is shared between multiple people. Read/write boolean. |


---


### setSubject {#setSubject}

| Name | Description |
| --- | --- |
| setSubject (String) | Returns or sets the subject of a presentation. Read/write String. |


---


### setTitle {#setTitle}

| Name | Description |
| --- | --- |
| setTitle (String) | Returns or sets the title of a presentation. Read/write String. |


---


### setTotalEditingTime {#setTotalEditingTime}

| Name | Description |
| --- | --- |
| setTotalEditingTime (double) | Total editing time of a presentation. Read/write double. |


---


### set_Item {#set_Item}

| Name | Description |
| --- | --- |
| set_Item (String, Object) | Returns or sets the custom property associated with a specified name. Read/write Object. Value can be int, float, String, boolean or Date. |


---


