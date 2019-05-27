# TRAVLR Code Test - Accommodation Full Stack

## Overview

The task is to build a basic hotel inventory system in .net core (C# or F#).

## Domain and Business Rules

A Hotel has a name, address, latitude, longitude, commission rate, and a list of rooms.

Each room has a name, max occupancy, net rate and a sell rate, currency code, and a list of amenities that are included in the room. Rooms also have a random unique 7 character access code that should not be exposed to the users/client.

- Each hotel can have a maximum of 5 rooms.
- The sell rate is the net rate plus commission.
- There should be 10 possible amenities to choose from.

## Tasks

1. Create the entities, aggregates and value objects to model this domain.

2. Create a database that will store this data

3. Implement the ability to read and write the object data to/from the database

4. Create an api that exposes a view model of the domain model to a client

5. Create a web client that allows the creation, editing and deletion of accommodation and rooms

6. Create an API that supports create, update and delete use cases of all entities

7. Implement 1 automated test each for frontend and backend layers.

## Notes

Consider appropriate business rules that would apply in a real world ecommerce scenario and ensure invariants are enforced.

Use the type system to ensure correctness of the data in the application layer, and use appropriate types in the database.

We should not be able to persist invalid data.

Make the UI responsive for desktop and mobile

If you are only a frontend dev, mock out the data from the server and persist on the client side.  If you are mainly backend, don't focus too much on the UI. Spend the most time on the areas of your strength.

Just FYI We use Vue.js in house on the frontend.

## Evaluation

The application should be bootable by running `./scripts/run` and tests should be runnable with `./scripts/test`.  Setup should be a simple checkout and `dotnet restore`.

Please commit regularly with descriptive commit messages along the way.

Share your git repo privately with [@3000](https://github.com/3000) [@krisanalfa](https://github.com/krisanalfa) [@gusmanwidodo](https://github.com/gusmanwidodo) [@clayton-travlr](https://github.com/clayton-travlr) on github (we dont want answers getting public)

You are free to choose another technical stack other than dotnet core but keep in mind if we cant get it to run in under 5 minutes on our macs we probably arent going to get to review it :)
