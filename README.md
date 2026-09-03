# HaoChia_TL — v1-based refinement

Base: `HaoChia_TL_rebase_v1`.

This revision returns both `web/` and `phone/` to the v1 rebase structure, then applies only the requested asset/layout changes. The current guide module is preserved.

Uploaded assets are stored under `shared/assets/tl/`. SVGs with Illustrator-linked photos were repaired to use local `pigs.jpg` / `avocados.jpg`.


## Asset alignment pass
- Updated asset47-p1-bg, asset45-p2-bg, fab desktop/mobile.
- Desktop asset45 shifted up 100px; asset46 enlarged ~20%; first paragraph lowered ~10%.
- asset8 and asset31 clouds enter once from outside the viewport with ease-in and finish flush to the browser edges.


## Desktop asset alignment v3
- asset45-p2-bg moved down 50px from the previous pass.
- asset31-cloud follows the same vertical shift.
- Efficient group moved 20px left.
- First paragraph moved 10px up.
- asset8-cloud enters immediately from +50px right overflow; asset31-cloud enters on scroll from -50px left overflow.
- Cloud transitions shortened to 280ms ease-in.
