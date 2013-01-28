Movies Workflow for Alfred 2.0
======================
A workflow for Alfred 2.0 which lets you quickly lookup movies and actors on IMDb and OMDb.

![](http://f.cl.ly/items/3W2E0W2S2I3o0H0j3r0l/alfred-movies-workflow.png)

The workflow is inspired by this workflow written by Robert Hovath. While the workflow developed by Hovath is great, I wanted to be able to search for actors and therefore I decided to create a workflow which pulls its information from IMDbs API.

However, the API provided by IMDb is unofficial and undocumented so I don't know of any way to pull detailed information from them, so I ended up retrieving information for a specific movie from OMDb.

The workflow uses one single command.

- **m [query]** Looks up a movie, TV series or actor matching the query. If a movie or TV series is selected, detailed information will be loaded from OMDb and shown. The detailed information includes the option for watching plot summary and a poster in quick look, view a list of actors in Alfred and view a trailer on YouTube. If an actor is selected, the corresponding IMDb website will be opened.

About
===
The workflow is developed by [@simonbs](http://twitter.com/simonbs/) and is inspired by Robert Hovath.