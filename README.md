# fedora-atomic-images

My customized versions of the official Fedora Atomic Desktop OCI images

Images based on the following atomic spins are built daily:
* Silverblue
* Sway Atomic

## Changes from base images

* Adds:
  *  `alacritty`, `distrobox`, `fzf`, `mbpfan`, `ripgrep`
  *  automatic daily system updates via `rpm-ostreed`
  *  automatic daily flatpak updates
  *  public key and configurations required to verify these signed images
* Removes:
  *  `firefox`
  *  desktop-specific automatic update systems
