## Ace System
- **`+` (Inbox)**: Temporary place for new notes
- **Atlas**: Knowledge repository (movies, definitions, quotes, ideas)
- **Calendar**: Time-based notes (daily, quick, weekly sections)
- **Efforts**: Project management for ongoing projects
- **x (System)**: Organizational support
#### Watch Later (MOC)
- Supports multiple content views based on `type` property
- Fill out `image` property to display covers
- Automatically collects all files with the `#watch-later` tag.
#### Drawings (MOC)
- Navigate through your Excalidrawings
- Automatically collects all files in the `x/drawings` directory.

---
## Hotkeys
- **Ctrl + R/Ctrl + U**: Create a quick note in the `calendar/quick` directory for tasks or fleeting thoughts.
- **Ctrl + N**: Create a new empty note in the `+` (Inbox) directory.
- **Alt + K**: Select and insert a template into the current note.
- **Ctrl + O**: Global search across all note titles and content. (Omnisearch)
- **Ctrl + F**: Search for text within the current active note.
- **Ctrl + P**: Command palette (access to all system commands and hotkeys).
- **Ctrl + ,**: Open settings.
- **Ctrl + G**: Open Graph.
- **Ctrl + E**: Reading mode on/off.
- **Ctrl + Space**: Create a new Excalidraw Sketch.
- **Ctrl + S**: Toggle left sidebar. 
- **Ctrl + L**: Toggle right sidebar.
- **Alt + L**: Switch Dark/Light mode.

---
## Workflow
1. **Daily Management**: Start by opening the current Daily Note via the calendar. It serves as your primary hub for the day.
2. **Quick Notes and Task Tracking**: Use `Ctrl + U` to create rapid-entry notes for tasks or ideas. 
	- These are automatically tracked in your Daily and Weekly Notes via the `day` and `week` properties. 
	- Once marked as done, the note disappears from its corresponding daily and weekly notes.
3. **Content Creation**: Use `Ctrl + N` for new files. You can apply a base template with `Alt + K` and add the `#watch-later` tag to sync it with the Watch Later MOC.
4. **Sketches**: Create a new drawing via the sidebar or **access existing ones** through the [[Drawings]] MOC.

## Rules: 
1. **Do not rename daily or weekly notes.** 
	The **Bases** plugin relies on these specific filenames for navigation; renaming them will break your dashboard and links.

## Recommendations:
1. **Use the `YYYY-MM-DD` date format exclusively.** 
	This ensures consistent sorting and seamless integration with the vault's automated workflows.
2. **Prioritize linking over new folders.** 
	The current folder structure is sufficient. Focus on connecting notes via links` to keep the vault organized and scalable.
