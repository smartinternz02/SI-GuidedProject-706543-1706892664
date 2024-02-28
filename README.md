# Craferia Project

Craferia is an online platform for handcrafts shopping. It provides a wide platform to small-scale producers so that their creativity thrives.

## Modules Overview

### Home Decor Module

This module contains classes for various home decor items such as showpieces, wall decor, home accents, and lamps/lightings.

- **Showpiece**: Represents a decorative item or figurine with attributes like name, material, and price.
- **WallDecor**: Represents decorative items for walls with attributes like name, material, dimensions, and price.
- **HomeAccents**: Represents small decorative items for home with attributes like name, category, and price.
- **Lamp**: Represents lamps or lightings with attributes like name, material, price, and wattage.

### Handmade Furnitures Module

This module contains classes for various handmade furniture items such as bamboo furniture and outdoor furniture.

- **BambooFurniture**: Represents furniture made from bamboo with attributes like name, type, and price.
- **OutdoorFurniture**: Represents outdoor furniture with attributes like name, material, price, and weatherproof status.

### Tests Module

This module contains test cases to validate the functionality of the classes in the Home Decor module.

- **TestHomeDecor**: Contains unit tests for Showpiece and WallDecor classes.

## Usage

To use this code, you can instantiate objects of the classes provided in the respective modules. For example:

```python
from home_decor.showpieces_figurines import Showpiece
from home_decor.wall_decor import WallDecor

# Create a showpiece object
showpiece = Showpiece("Ceramic Vase", "Ceramic", 25.99)
showpiece.display_info()

# Create a wall decor object
wall_decor = WallDecor("Abstract Painting", "Canvas", "24\" x 36\"", 59.99)
wall_decor.display_info()
