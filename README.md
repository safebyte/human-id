#### Generates human readable IDs by chaning common short words of the english language. ####

Using words (instead of numbers) to identify datasets provides various advantages when humans are involved. `human-id` generates word ids from a pool of 10 006 400 unique IDs.

0 dependencies.

## Examples

- FortyGhostsTalk
- CalmPanthersDream
- TastyRocksSparkle
- HealthyCowsSmile
- AfraidWallsExist
- StrangeCarsRush
- TwoKangaroosSing
- HappyDolphinsJump

## Install

```
$ npm install --save human-id
```

## Usage

```
const nameId = require('name-id');
const id = nameId();

// RareGeckosJam
nameId();

 // rare-geckos-jam
nameId({separator:'-',capitalize:false});
```