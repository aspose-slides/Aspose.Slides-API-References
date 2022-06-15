---
title: NormalViewProperties
type: docs
weight: 0
url: /php-java/normalviewproperties/
---

# NormalViewProperties class

 Represents normal view properties. The normal view consists of
 three content regions: the slide itself, a side content region, and a bottom content region.
 

## Methods

| name | return type | description |
| --- | --- | --- |
| [getHorizontalBarState](/slides/php-java/normalviewproperties/gethorizontalbarstate/)() | int | Specifies the state that the horizontal splitter bar should be shown in. A horizontal splitter bar separates the slide from the content region below the slide. |
| [getPreferSingleView](/slides/php-java/normalviewproperties/getprefersingleview/)() | boolean | Specifies whether the user prefers to see a full-window single-content region over the standard normal view with three content regions. If enabled, the application may choose to display one of the content regions in the entire window. Read/write boolean. |
| [getRestoredLeft](/slides/php-java/normalviewproperties/getrestoredleft/)() | INormalViewRestoredProperties | This element specifies the sizing of the side content region of the normal view, when the region is of a variable restored size(neither minimized nor maximized). Read opnly INormalViewRestoredProperties. |
| [getRestoredTop](/slides/php-java/normalviewproperties/getrestoredtop/)() | INormalViewRestoredProperties | This element specifies the sizing of the top slide region of the normal view, when the region is of a variable restored size(neither minimized nor maximized). Read only INormalViewRestoredProperties. |
| [getShowOutlineIcons](/slides/php-java/normalviewproperties/getshowoutlineicons/)() | boolean | Specifies whether the application should show icons if displaying outline content in any of the content regions of normal view mode. Read/write boolean. |
| [getSnapVerticalSplitter](/slides/php-java/normalviewproperties/getsnapverticalsplitter/)() | boolean | Specifies whether the vertical splitter should snap to a minimized state when the side region is sufficiently small. Read/write boolean. |
| [getVerticalBarState](/slides/php-java/normalviewproperties/getverticalbarstate/)() | int | Specifies the state that the vertical splitter bar should be shown in. A vertical splitter bar separates the slide from the side content region. |
| [setHorizontalBarState](/slides/php-java/normalviewproperties/sethorizontalbarstate/)(int) | void | Specifies the state that the horizontal splitter bar should be shown in. A horizontal splitter bar separates the slide from the content region below the slide. |
| [setPreferSingleView](/slides/php-java/normalviewproperties/setprefersingleview/)(boolean) | void | Specifies whether the user prefers to see a full-window single-content region over the standard normal view with three content regions. If enabled, the application may choose to display one of the content regions in the entire window. Read/write boolean. |
| [setShowOutlineIcons](/slides/php-java/normalviewproperties/setshowoutlineicons/)(boolean) | void | Specifies whether the application should show icons if displaying outline content in any of the content regions of normal view mode. Read/write boolean. |
| [setSnapVerticalSplitter](/slides/php-java/normalviewproperties/setsnapverticalsplitter/)(boolean) | void | Specifies whether the vertical splitter should snap to a minimized state when the side region is sufficiently small. Read/write boolean. |
| [setVerticalBarState](/slides/php-java/normalviewproperties/setverticalbarstate/)(int) | void | Specifies the state that the vertical splitter bar should be shown in. A vertical splitter bar separates the slide from the side content region. |
