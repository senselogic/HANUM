![](https://github.com/senselogic/HANUM/blob/master/LOGO/hanum.png)

# Hanum

Hash code enumeration builder and updater.

## Sample

Input code:
```csharp
public enum DWARF : int
{
    Balin = 1,
    Bifur = 2,
    Bofur = 3,
    Bombur = 4,
    Dwalin = 5,
    Thorin = 6
}

// ~~

public enum ELF : uint
{
    Arwen,
    Elrond,
    Galadriel,
    Legolas,
    Luthien,
    Tauriel
}
```

Output code :
```csharp
public enum DWARF : int
{
    Balin = -1649857601,
    Bifur = 1877047393,
    Bofur = -851015153,
    Bombur = -1336084518,
    Dwalin = -516229278,
    Thorin = -1808157577
}

// ~~

public enum ELF : uint
{
    Arwen = 1222194504u,
    Elrond = 2237347981u,
    Galadriel = 3123839678u,
    Legolas = 1623673708u,
    Luthien = 1077404370u,
    Tauriel = 3717155441u
}
```

## Version

1.0

## Author

Eric Pelzer (ecstatic.coder@gmail.com).

## License

This project is licensed under the GNU General Public License version 3.

See the [LICENSE.md](LICENSE.md) file for details.
