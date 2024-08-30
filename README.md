## ReactJS Keeper App

ReactJS Keeper App is a fully front-end note-taking application built using a component-based architecture, incorporating data deletion functionality.

### Key Components:

- NoteList: Displays a list of all notes, including titles and summaries.
- NoteItem: Renders individual notes with details like content, tags, and creation time.
- NoteForm: Handles the creation and editing of notes, allowing users to input text, format content, and add tags.
  Data Deletion Functionality:

- Delete Button: Each NoteItem component includes a "Delete" button that directly sends a request to a local storage or browser database to delete the corresponding note.
- Data Update: Upon successful deletion, the NoteList component is updated to reflect the removal of the note from the list.

