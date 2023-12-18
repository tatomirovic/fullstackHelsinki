```mermaid
sequenceDiagram
    participant browser
    participant server

    browser->>browser: redrawNotes()

    browser->>+server: POST https://studies.cs.helsinki.fi/exampleapp/new_note_spa
    server-->>-browser: 201 Created response

```