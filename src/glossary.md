# Glossary

### Velocity

The speed at which a projectile travels, usually given in meters per second (m/s).

### Muzzle Velocity

Muzzle velocity refers to the [velocity](#velocity) of a projectile as it leaves the barrel or muzzle device.

### Velocity Factor (Vf)

This value is calculated from the [velocity](#velocity) of a projectile and ranges from `1.0` to `0.0`. It is multiplied by the [damage](#damage) and [penetration power](#penetration-power).

### Ballistic Coefficient

The ballistic coefficient (BC) of a body is a measure of its ability to overcome air resistance in flight. It is inversely proportional to the negative acceleration: a high number indicates a low negative acceleration — the drag on the body is small in proportion to its mass.

Or in simple words: the higher the value, the better the flight characteristics and the less energy loss over the distance.

More details on [Wikipedia](https://en.wikipedia.org/wiki/Ballistic_coefficient)

### Damage

Specifies the number of health points that are deducted when a body part is hit.

### Armor Damage

Is given in absolute or relative numbers.

If absolute, then it indicates the number of durability points that are deducted when the projectile hits the armor.

If relative, then the absolute value is calculated from the [penetration power](#penetration-power), the [armor material](#armor-material), the [armor class](#armor-class) and whether the projectile has penetrated the armor or not.

### Blunt Damage

The damage passed through to the part of the body protected by the armor if the projectile does not penetrate.

The value is calculated from the damage permeability and [resistance](#armor-resistance) of the armor, as well as the [penetration power](#penetration-power) and [damage](#damage) of the projectile.

### Penetration Power

Indicates the ability of ammunition to penetrate body armor or, to a lesser extent, world objects.

### Penetration Chance

Indicates the probability of penetrating armor.

The value is calculated from the [penetration power](#penetration-power) and the [armor resistance](#armor-resistance).

### Fragmentation Chance

Indicates the probability of a projectile fragmenting in a body. The number of fragments varies from ammunition to ammunition.
Each fragment deals 50% additional damage to the part of the body that is hit.

Note: Currently, ammunition does not fragment if the [penetration power](#penetration-power) value is below `20`.

### Armor Class

Indicates the class of the armor. Armors are divided into 6 different classes, of which 6 is the most resistant class.

### Armor Durability

Indicates how much [armor damage](#armor-damage) an armor can withstand before it loses its protective effect. The more durability the armor loses, the more it loses its [resistance](#armor-resistance).

### Armor Material

The material indicates the destructibility and reparability of armor.

### Armor Resistance

It indicates the armor's resistance to external damage.

It's calculated from the [class](#armor-class) and [durability](#armor-durability) of the armor.

### Zeroing

TODO
