==============================================================================================
🐾 DesktopPet
A floating desktop companion that walks, sits, sleeps, and sparkles — built for rebellion, joy, and cursor-tethered love.

✨ Features
🐶 Choose your pet: Dog, Cat, Axolotl (Capybara in update 2.2)

🧭 Roams the screen with directional walking and bounce logic

💤 Click to cycle: Sitting → Walking → Sleeping

🖱️ Hold for 2 seconds → drag pet with cursor

🌈 Rainbow trail while dragging

🧠 Tray menu: Help, Teach Tricks, Buy Treats, Swap Pet, Exit

🖼️ Transparent window — no white box, just pure pixel soul

🚀 Setup
Clone or download the project

Add your pet sprites to Resources/<PetName>/

Required files: Sit1.png, Sleep1.png, Walk1.png

Optional directional: WalkUp.png, WalkDown.png, WalkLeft.png, WalkRight.png

Open terminal in project folder

Run:

bash
dotnet build
dotnet run
🗂️ Folder Structure
Code
DesktopPet/
├── Resources/
│   ├── Dog/
│   ├── Cat/
│   ├── Axolotl/
│   └── Capybara/ (coming in update 2.2)
├── settings.json
├── Program.cs
├── PetForm.cs
├── PetSelector.cs
├── DesktopPet.csproj
🧩 Controls
Click pet → cycle behavior

Hold for 2 seconds → drag mode

Tray menu → tricks, treats, swap, exit

Pet auto-walks and bounces off screen edges

🛠️ Customization
Add new pets by creating a folder in Resources/

Drop in matching sprite files

Pet names must match folder names exactly

Want sparkles, sound effects, or badge overlays? Fork it and riff
