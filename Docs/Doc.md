# Syde Documentation

## Loading

```lua
Local SydeUI = loadstring(game:HttpGet("https://raw.githubusercontent.com/yarrosvault/syde/refs/heads/main/source",true))()
```

## Loader (Optional But Somethings Will Not Be Available)

```lua
syde:Load({
	Logo = '7488932274',
	Name = 'Lavender',
	Status = 'Stable', -- {Stable, Unstable, Detected, Patched}
	Accent = Color3.fromRGB(251, 144, 255), -- Window Accent Theme
	HitBox = Color3.fromRGB(251, 144, 255), -- Window HitBox Theme (ex. Toggle Color)
	AutoLoad = false, -- Does Not Work !
	Socials = {    -- Allows 1 Large and 2 Small Blocks
		{
			Name = 'Syde';
			Style = 'Discord';
			Size = "Large";
			CopyToClip = true -- Copy To Clip (coming very soon)
		},
		{
			Name = 'GitHub';
			Style = 'GitHub';
			Size = "Small";
			CopyToClip = true
		}
	}
})
```

