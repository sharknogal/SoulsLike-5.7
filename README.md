# SoulsLike Blueprint Combat Prototype

Portfolio repository for a content-only Unreal Engine Blueprint prototype focused on third-person soulslike combat interactions.

## What This Shows

- Blueprint-based player combat character and player controller setup.
- Weapon and equippable actor hierarchy for base weapons, dual weapons, pickups, and concrete sword variants.
- Combat, collision, state, and stat components split into reusable Blueprint components.
- Animation notify Blueprints for attack continuation, collision tracing, combat reset, weapon attachment, and character rotation windows.
- HUD/stat-bar widgets and enhanced input assets used by the prototype.

## Project Details

- Engine association: Unreal Engine 5.7
- Main map: `Content/Maps/ThirdPersonMap.umap`
- Default mode: `Content/CombatSystem/Blueprints/BP_ThirdPersonGameMode`
- Main character Blueprint: `Content/CombatSystem/Blueprints/BP_CombatPlayerCharater`

## Controls

These bindings are defined in `Config/DefaultInput.ini`.

- `Left Mouse Button`: light attack
- `Alt + Left Mouse Button`: heavy attack
- `Left Control`: dodge
- `Left Shift`: sprint
- `R`: toggle combat
- `Caps Lock`: toggle walk
- `F`: interact

## Asset Notice

This public repository intentionally omits third-party, sample, marketplace, and course asset folders such as Paragon, Mixamo, starter VFX, mannequin/sample content, and `Content/CombatSystem/CourseFiles`.

Those assets are not redistributed here. To run the full local prototype, restore the omitted assets from their original licensed sources in the same folder paths.

## Opening The Project

```powershell
git lfs install
git clone https://github.com/sharknogal/SoulsLike-5.7.git
cd SoulsLike-5.7
```

Then open `SoulsLike.uproject` with Unreal Engine 5.7.

Because licensed assets are omitted from the public repository, the project is primarily intended to demonstrate Blueprint structure and implementation scope. The complete local version may contain additional art, animation, and VFX dependencies.
