# 提示词模板

将尖括号内容替换为当前照片信息。保持提示词简洁，但每次都重复身份、手部和正负形不变量。

## 共享基础图

```text
Use case: identity-preserve photo edit.
Input images: Image 1 is the only edit target.
Primary request: Create a shared retouched film base for two later collage variants.
Subject group: <主体以及必须保留的手持物、服饰和互动对象>.
Color and texture: restrained vintage Fujifilm-inspired rendering; warm creamy highlights, muted amber midtones, subtle olive/sage shadows, lifted blacks, soft highlight roll-off, fine irregular 35mm grain, mild halation, matte finish, delicate painterly blending only in broad color transitions.
Portrait retouching: naturally reduce temporary pimples, acne marks, patchy redness and uneven skin tone while preserving pores and real skin texture.
Constraints: preserve exact identity, facial geometry, ethnicity, expression, gaze, teeth, glasses, hairstyle, pose, hands, finger count, clothing, jewelry, held objects, packaging and existing printed lettering; preserve the original scene and framing; do not add or remove objects.
Avoid: face reshaping, plastic skin, heavy makeup, over-whitening, HDR, teal-orange grade, full illustration, new text, watermark.
```

## 常规版

```text
Use case: identity-preserve compositing.
Asset type: vertical positive/negative analog paper collage.
Input images: Image 1 is the shared retouched film base. Any additional image is a style reference only.
Primary request: Create one regular paper-collage version built around the exact subject group <主体组>.
Composition: upper section on warm cream handmade paper with the complete photographic subject cutout centered and surrounded by generous negative space; lower section uses the source background with the same subject removed, leaving a clean warm-ivory paper void that exactly matches the upper cutout; align both shapes on the same visual axis; add a narrow blank paper seam.
Decoration: use 5–9 sparse low-contrast motifs derived from <照片专属母题>; use faded paper stars only as a fallback; never cover the face, hands, important text or silhouette boundary.
Materials: matte aged paper, fine fibers, slight hand-cut irregularity, soft glue shadow, restrained moss or sage offset backing, subtle analog grain.
Critical invariants: the lower shape is completely empty—no ghost, faded duplicate, face or second person; preserve identity, face, teeth, glasses, hair, hands, fingers, pose, held objects and existing packaging text.
Text: none unless supplied verbatim by the user.
Avoid: textile-heavy effects, thick outlines, duplicated subjects, altered anatomy, copied reference text, UI, logos, watermark.
```

## 手作版

```text
Use case: identity-preserve subtle material refinement.
Asset type: restrained handmade textile-and-paper positive/negative collage.
Input images: Image 1 is the shared retouched film base; Image 2 is the regular version and exact composition anchor.
Primary request: Keep the regular version's subject, positive/negative outlines, scale, axis, palette and spacing unchanged; add only understated premium handcraft detail.
Material balance: approximately 85% paper and photography, 15% textile detail.
Upper cutout: add an extremely thin irregular oatmeal cotton-paper rim and a 2–4 mm muted fabric backing visible only in a few places; add about 8–12 tiny running stitches around selected outer-edge segments; keep thread outside the photographic subject.
Lower void: keep predominantly warm ivory paper; add a faint tone-on-tone fine-knit impression only in part of the shape; add restrained cotton fuzz, a few microscopic fibers and a delicate inner shadow.
Seam and decoration: use one thin torn cotton-paper seam with three or four nearly invisible tack stitches; use mostly flat paper motifs plus at most one tiny embroidered accent and one tiny felt accent.
Critical invariants: preserve exact identity, face, teeth, glasses, hair, skin texture, pose, hands, finger count, held objects and packaging text; keep the lower void empty and matched to the upper outline.
Avoid: chunky knitting, thick felt, coarse burlap, blanket stitching, large yarn loops, dangling threads, lace, bows, buttons, sequins, crowded craft decoration, altered anatomy, new text, watermark.
```

## 迭代模板

```text
Change only <单一失败项>. Keep the exact identity, subject cutout, positive/negative outlines, composition, palette, spacing and all other materials unchanged. Re-check hands, face, lower empty silhouette and existing printed text.
```
