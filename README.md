# Pr0gramm Message Markup Language

Eine Auszeichnungssprache für Nachrichten im Pr0.

## Tags

pmml ist Tagbasiert.

Dabei unterscheiden sich zwei Arten von Tags:

### Block

Ein Block-Tag muss zwingend der einzige Block-Tag in einer Nachricht sein und zu Beginn stehen. Alle weiteren Block-Rags werden abgeschnitten. Weiterer Inhalt wird als Unterschrift verwendet.

#### Liste der Block-Tags:

- Image

### Inline

Ein Inline-Tag wird wie Text ausgegeben und kann beliebig häufig eingesetzt werden.

#### Liste der Inline-Tags:

- Icon

## Sytax

Tags beginnen mit einer eckigen Klmmer auf, dem Tagnamen, den Prametern (in Klammern, Wert in Anführungszeichen und kommergetrennt) und einer eckigen Klammer zu.

Beispiele:

- `[Image("base64_string")]`
- `[Icon("icon_key")]`
