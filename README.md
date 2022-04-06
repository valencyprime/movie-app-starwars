## Movies App w/ React - Star Wars API (https://swapi.dev)

## Problems Encountered While Building The App Are Listed Below....

## TASK:

Create a small app using React that lists the names of Star Wars movies in a dropdown and the opening crawl of the selected movie below the selection along with a list of the characters that appear in that movie.

## General Requirements:

- The UI should have a basic theme of black and yellow; visual design is low in the priority list.

- Movie names in the dropdown to be sorted by release date from earliest to newest.

- There should be no movie selected initially and the app should show the Star Wars logo instead of movie information.

- The opening crawl of the selected movie should be animated, a simple scrolling marquee text would be sufficient.

- Keep your application source code on a public Github repository.

## Character List Requirements:

- All characters that appear in that movie should be listed showing name, gender, and height in the form of a table.

- Gender can be shown as an icon or abbreviation to save horizontal space.

- Character list can be sorted by clicking on the table headers.

- Clicking on the same header twice toggles the sort order by the field between ascending and descending.

- There should also be a gender filter selection right above the list so that either all characters are listed or only the selected gender are listed.

- The last row of the table should show the total number of characters currently visible on the list.

- The last row should also show the sum of the heights of the characters currently visible.

- The sum of heights should be shown both in cm and in feet/inches in parenthesis, for example, 170 cm (5ft/6.93in)

## Problems Encountered While Building The Star Wars React App:

- As regards the lists containted in the General Requirements for the Star Wars React App, ALL BUT ONE was achieved, which is the opening crawl for the selected movie.

- I made use of the online browser based code editor, Codesandbox, to build a responsive react video player for the opening crawl.

- While in Codesandbox, I made use of a react player component from 'CookPete' because the component allows for the playing variety of videos from URLs, YouTube, Facebook, Twitch, SoundClound and a bunch of different options.

- But I encountered errors creating the videos of the opening crawl for the Star Wars movies from the Gatsby Default Starter player.

- The Gatsby Default Starter Player couldn't render the YouTube Link video for the opening crawl when the YouTube Link itself works fine on a browser.

- Furthermore, I was unable to achieve the Character List Requirements given that the API Link from https://swapi.dev for the people (i.e. https://swapi.dev/api/people/) in any selected movie appears to be broken.

- Whenever I paste the API Link and hit the save button, the entire contents on movie app disappears. It wasn't giving the intended results on the movie app.

- On the positive side, only the API Link for the films (i.e. https://swapi.dev/api/films/) worked successfully as it should.

- I also tried to include an overview for each of the Star Wars movie but the API Link couldn't provide that as well. It only provided the movie list.
