This page provides additional visual results to address the reviewers' questions regarding severe rotational ambiguity and extreme partiality.

---

### Challenge 1: Severe Symmetrical Ambiguity

In response to the concern about rotational cues, we show that our method successfully aligns full reconstructions (center) even when the partial input (left) lacks distinctive geometric features. As shown in the final result (right), the texture from the input is correctly mapped onto the reconstructed mesh, achieving accurate pose alignment.

![Challenge 1 Result](./assets/challenge1.png)

*Figure 1: Visualization for Challenge 1. Left: Partial input (nearly spherical/cylindrical). Center: Full symmetric reconstruction. Right: Our aligned, textured result. Note that our method resolves the rotational ambiguity to achieve correct alignment.*

---

### Challenge 2: Extreme Partiality

To address the concern about data-driven hallucination under extreme partiality, we show reconstructions where a significant portion of the mesh is missing (left). Despite the severe missingness, our method generates plausible geometry (center) and completes the full scene representation. The final aligned result (right) demonstrates the robustness of our pipeline in filling in missing details.

![Challenge 2 Result](./assets/challenge2.png)

*Figure 2: Visualization for Challenge 2. Left: Severely partial input with significant missing data (e.g., the base of the objects). Center: Our completed reconstruction. Right: The final alignment results.*

---

### Note on Double-Blind

In accordance with the double-blind policy, this repository and all assets have been anonymized. Metadata has been stripped from the image files.
