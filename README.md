# InMoov Animatronic Head

An open-source [InMoov]([[https://inmoov.fr/](https://inmoov.fr/headi2/)]) head build, focused on the software side — currently working toward eye tracking. Goal is to understand the full mechatronic stack end to end (mechanical, electrical, software) rather than just the parts that are comfortable.

## Status: Hardware assembled, software not started

- ✅ 3D-printed head parts printed and assembled
- ✅ Servo motors mounted in the head
- ⬜ Board/controller — not finalised yet 
- ⬜ Servo control software
- ⬜ Eye tracking (the current focus)

This is a living document — it'll get updated as decisions get made and code gets written, not just at the end.

## Stack

**TBD.** Board choice isn't locked in yet. Will update this section (and the `/software` folder structure) once that's decided.

## Repo structure

```
/hardware   — STL files, wiring notes, servo specs
/software   — control code (once it exists)
/docs       — build notes, decisions, dead ends
/media      — photos and video of the physical head
```

## Photos

*(Add 2–3 photos here of the assembled head — front view, servo mounting close-up, and a wiring shot if you have one. Drop the image files in `/media` and reference them like:)*

```markdown
![Head assembled, front view](media/head-front.jpg)
![Servo mounting](media/servo-closeup.jpg)
```

## Why this project

The next decade of engineering gets decided by who can get hardware and software actually talking to each other. This head is where I'm learning that — starting with getting motors to move on command, working up to a system that can actually track and follow a face.

## Log

**14/09/26** — Repo created. Head fully assembled with servos mounted. Next step: pick a board and get a single servo moving from code before touching eye tracking.
