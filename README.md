# Library Management System

This is an old Library Management System written in C++. The system allows for the addition, deletion, borrowing, and returning of library items such as books, films, and music albums. This project was done as a piece of coursework for "Object Oriented Computer Programming" in my undergraduate degree in Electical and Electronic Engineering and was my first project using object oriented techniques in C++.

## Features

- Add new library items (books, films, music albums)
- Delete existing library items
- Borrow library items
- Return borrowed items
- Search for a library item by its title
- Track the due date of borrowed items

## Classes

The project is built around several main classes:

- `Entry`: This is the base class for all items in the library. It holds common information like name, due date, and borrowed status.

- `Book`, `Film`, `MusicAlbum`: These classes inherit from `Entry` and represent specific types of library items.

- `Catalogue`: This class manages the library items. It holds a collection of `Entry` objects and provides methods for adding, deleting, borrowing, returning, and searching items.


## Usage

The Library Management System is a console application. It prompts the user with a menu of actions to choose from:

1. Add an item to the library.
2. Delete an item from the library.
3. Borrow an item from the library.
4. Return an item to the library.
5. Search for an item in the library.

Follow the on-screen prompts to perform the desired actions.


## License

This project is licensed under the MIT License.
