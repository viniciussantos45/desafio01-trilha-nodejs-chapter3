# desafio01-trilha-nodejs-chapter3

A TypeScript challenge from the [Rocketseat Ignite](https://www.rocketseat.com.br/ignite) Node.js bootcamp (Chapter 3) focused on building **repository classes with TypeORM** and working with entity relationships.

## Objective

The objective of this challenge is to implement `UsersRepository` and `GamesRepository` using TypeORM, handling the many-to-many relationship between users and games, and validating the implementations with integration tests.

## Features

- List all users with their associated games
- List all games with their players
- Find a user by their ID or email
- Find games by technology name (partial match)

## Tech Stack

- Node.js
- TypeScript
- TypeORM (SQLite)
- Jest

## Getting Started

```bash
yarn install
yarn typeorm migration:run
yarn test
```
