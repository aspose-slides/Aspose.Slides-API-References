---
title: NotesCommentsLayoutingOptions
type: docs
weight: 0
url: /php-java/notescommentslayoutingoptions/
---

# NotesCommentsLayoutingOptions class

 Provides options that control the look of layouting of notes and comments in exported document.
 

## Constructors

| name | description |
| --- | --- |
| [NotesCommentsLayoutingOptions](/php-java/notescommentslayoutingoptions/notescommentslayoutingoptions/)() | Default constructor. |

## Methods

| name | return type | description |
| --- | --- | --- |
| [getCommentsAreaColor](/php-java/notescommentslayoutingoptions/getcommentsareacolor/)() | Color | Gets or sets the color of comments area (Applies only if comments are displayed on the right). Default is java.awt.Color#BLUE. |
| [getCommentsAreaWidth](/php-java/notescommentslayoutingoptions/getcommentsareawidth/)() | int | Gets or sets the width of the comment output area in pixels (Applies only if comments are displayed on the right). Minimal and default value is 150. |
| [getCommentsPosition](/php-java/notescommentslayoutingoptions/getcommentsposition/)() | int | Gets or sets the position of the comments on the page. Default is CommentsPositions#None. |
| [getNotesPosition](/php-java/notescommentslayoutingoptions/getnotesposition/)() | int | Gets or sets the position of the notes on the page. Default is NotesPositions#None. |
| [getShowCommentsByNoAuthor](/php-java/notescommentslayoutingoptions/getshowcommentsbynoauthor/)() | boolean | Gets or sets the visibility of comments that do not have an author. If true then comments will be displayed. (Applies only if comments are displayed). Default value is false. |
| [setCommentsAreaColor](/php-java/notescommentslayoutingoptions/setcommentsareacolor/)(Color) | void | Gets or sets the color of comments area (Applies only if comments are displayed on the right). Default is java.awt.Color#BLUE. |
| [setCommentsAreaWidth](/php-java/notescommentslayoutingoptions/setcommentsareawidth/)(int) | void | Gets or sets the width of the comment output area in pixels (Applies only if comments are displayed on the right). Minimal and default value is 150. |
| [setCommentsPosition](/php-java/notescommentslayoutingoptions/setcommentsposition/)(int) | void | Gets or sets the position of the comments on the page. Default is CommentsPositions#None. |
| [setNotesPosition](/php-java/notescommentslayoutingoptions/setnotesposition/)(int) | void | Gets or sets the position of the notes on the page. Default is NotesPositions#None. |
| [setShowCommentsByNoAuthor](/php-java/notescommentslayoutingoptions/setshowcommentsbynoauthor/)(boolean) | void | Gets or sets the visibility of comments that do not have an author. If true then comments will be displayed. (Applies only if comments are displayed). Default value is false. |