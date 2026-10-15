# Supabase import report · 2026-10-15

Source: `SDS-7613-supabase-export-model.json`

## Blocking errors (0)

None.

## Value changes to existing tokens (6)

| set | token | before | after |
|---|---|---|---|
| primitive/color | Slate.rgba | "#rgb(66 85 99 / 25%)" | "rgb(66 85 99 / 25%)" |
| primitive/color | slate.rgba.08 | "#" | "rgb(66 85 99 / 8%)" |
| semantic/color-mode/light | text.tertiary | "{Navy.700}" | "{Navy.500}" |
| semantic/color-mode/light | icon.active | "{Blue.300}" | "{Blue-gray.300}" |
| semantic/border | border-width.outline.xs | "{border.width.sm}" | "{border.width.xs}" |
| semantic/border | border-width.outline.solid | "{border.style.solid}" | "border-width.solid" |

## Type changes to existing tokens (1)

| set | token | before | after |
|---|---|---|---|
| semantic/border | border-width.outline.solid | border | borderWidth |

## Light/dark parity problems introduced by this import (0)

None.

## Light/dark parity problems already in tokens/ (not blocking) (1)

| set | token | issue |
|---|---|---|
| component/color-mode/dark | data-grid.text.color.color | dark only |

## Quarantined tokens present in one mode only (not blocking, never pushed) (2)

| set | token | issue |
|---|---|---|
| supabase/component/color-mode/light | button.secondary.text.hover.label.color | quarantine, one mode only |
| supabase/component/color-mode/dark | data.grid.default.header.text.color | quarantine, one mode only |

## Quarantined to `supabase/` (not in tokens/, not in any theme) (67)

| set | token | value | exporter note |
|---|---|---|---|
| primitive/color | ash.50 | "#f8f9f9" | no Figma path mapped for Supabase token ash-50 |
| primitive/color | orange.250 | "#f3c781" | no Figma path mapped for Supabase token orange-250 |
| primitive/color | orange.350 | "#f39681" | no Figma path mapped for Supabase token orange-350 |
| primitive/color | orange.450 | "#c67839" | no Figma path mapped for Supabase token orange-450 |
| primitive/color | turquoise.150 | "#00c5d3" | no Figma path mapped for Supabase token turquoise-150 |
| primitive/color | turquoise.250 | "#55f4fc" | no Figma path mapped for Supabase token turquoise-250 |
| primitive/spacing | spacing.negative.10xs | "-24px" | no Figma path mapped for Supabase token spacing-negative-10xs |
| primitive/shadow | spread.1 | "1px" | no Figma path mapped for Supabase token spread-1 |
| primitive/shadow | spread.2 | "2px" | no Figma path mapped for Supabase token spread-2 |
| primitive/typography | font.family.open.sans | "Open Sans" | no Figma path mapped for Supabase token font-family-open-sans |
| primitive/typography | line.height.6xl | "1.222" | no Figma path mapped for Supabase token line-height-6xl |
| primitive/typography | line.height.7xl | "1.2" | no Figma path mapped for Supabase token line-height-7xl |
| semantic/color-mode/light | border.transparent | "{transparent}" | no Figma path mapped for Supabase token color-border-transparent |
| semantic/color-mode/light | chart.disabled.legend.item | "{Gray.400}" | no Figma path mapped for Supabase token color-chart-disabled-legend-item |
| semantic/color-mode/light | severity.info | "{Cyan.800}" | no Figma path mapped for Supabase token color-severity-info |
| semantic/color-mode/light | status.error | "{Red.100}" | no Figma path mapped for Supabase token color-status-error |
| semantic/color-mode/light | status.informational | "{Cyan.800}" | no Figma path mapped for Supabase token color-status-informational |
| semantic/color-mode/light | status.success | "{Green.200}" | no Figma path mapped for Supabase token color-status-success |
| semantic/color-mode/light | status.warning | "{Sunset.250}" | no Figma path mapped for Supabase token color-status-warning |
| semantic/color-mode/light | elevation.outline.default | {"x": "{X.0}", "y": "{Y.0}", "blur": "{blur.none}", "spread": "{spread.1}", "color": "{Gray.300}", "type": "dropShadow"} |  |
| semantic/color-mode/dark | border.transparent | "{transparent}" | no Figma path mapped for Supabase token color-border-transparent |
| semantic/color-mode/dark | chart.disabled.legend.item | "{Black.600}" | no Figma path mapped for Supabase token color-chart-disabled-legend-item |
| semantic/color-mode/dark | severity.info | "{Blue.50}" | no Figma path mapped for Supabase token color-severity-info |
| semantic/color-mode/dark | status.error | "{Red.50}" | no Figma path mapped for Supabase token color-status-error |
| semantic/color-mode/dark | status.informational | "{Blue.50}" | no Figma path mapped for Supabase token color-status-informational |
| semantic/color-mode/dark | status.success | "{Green.100}" | no Figma path mapped for Supabase token color-status-success |
| semantic/color-mode/dark | status.warning | "{Orange.275}" | no Figma path mapped for Supabase token color-status-warning |
| semantic/color-mode/dark | elevation.outline.default | {"x": "{X.0}", "y": "{Y.0}", "blur": "{blur.none}", "spread": "{spread.1}", "color": "{Black.400}", "type": "dropShadow"} |  |
| semantic/elevation | elevation.outline.focus | {"x": "{X.0}", "y": "{Y.0}", "blur": "{blur.none}", "spread": "{spread.2}", "color": "{Orange.400}", "type": "dropShadow"} | no Figma path mapped for Supabase token elevation-outline-focus |
| component/color-mode/light | button.danger.outline.active.background.color | "{Rose.35}" | no Figma path mapped for Supabase token button-danger-outline-active-background-color |
| component/color-mode/light | button.danger.outline.hover.background.color | "{Rose.30}" | no Figma path mapped for Supabase token button-danger-outline-hover-background-color |
| component/color-mode/light | button.filled.primary.background.focus | "{Blue.200}" | no Figma path mapped for Supabase token button-filled-primary-background-focus |
| component/color-mode/light | button.filled.primary.background.hover | "{Blue.200}" | no Figma path mapped for Supabase token button-filled-primary-background-hover |
| component/color-mode/light | button.filled.primary.text.hover | "{Gray.25}" | no Figma path mapped for Supabase token button-filled-primary-text-hover |
| component/color-mode/light | button.primary.text.active.icon.color | "{Blue.300}" | no Figma path mapped for Supabase token button-primary-text-active-icon-color |
| component/color-mode/light | button.secondary.text.hover.label.color | "{Blue-gray.200}" | no Figma path mapped for Supabase token button-secondary-text-hover-label-color |
| component/color-mode/light | calendar.today.number.text | "{Blue.100}" | no Figma path mapped for Supabase token color-calendar-today-number-text |
| component/color-mode/light | filter.tag.background | "{Gray.25}" | no Figma path mapped for Supabase token color-filter-tag-background |
| component/color-mode/light | filter.tag.border | "{Gray.300}" | no Figma path mapped for Supabase token color-filter-tag-border |
| component/color-mode/light | tab.border.selected | "{Blue.100}" | no Figma path mapped for Supabase token color-tab-border-selected |
| component/color-mode/light | tag.severity.undetermined.container.background.color | "{Stone.200}" | no Figma path mapped for Supabase token tag-severity-undetermined-container-background-color |
| component/color-mode/light | time.picker.selected.list.border.color | "{Gray.200}" | no Figma path mapped for Supabase token time-picker-selected-list-border-color |
| component/color-mode/dark | button.danger.outline.active.background.color | "{Rose.275}" | no Figma path mapped for Supabase token button-danger-outline-active-background-color |
| component/color-mode/dark | button.danger.outline.hover.background.color | "{Rose.250}" | no Figma path mapped for Supabase token button-danger-outline-hover-background-color |
| component/color-mode/dark | button.filled.primary.background.focus | "{Sky-blue.200}" | no Figma path mapped for Supabase token button-filled-primary-background-focus |
| component/color-mode/dark | button.filled.primary.background.hover | "{Sky-blue.200}" | no Figma path mapped for Supabase token button-filled-primary-background-hover |
| component/color-mode/dark | button.filled.primary.text.hover | "{Black.950}" | no Figma path mapped for Supabase token button-filled-primary-text-hover |
| component/color-mode/dark | button.primary.text.active.icon.color | "{Sky-blue.300}" | no Figma path mapped for Supabase token button-primary-text-active-icon-color |
| component/color-mode/dark | calendar.today.number.text | "{Sky-blue.100}" | no Figma path mapped for Supabase token color-calendar-today-number-text |
| component/color-mode/dark | filter.tag.background | "{Black.950}" | no Figma path mapped for Supabase token color-filter-tag-background |
| component/color-mode/dark | filter.tag.border | "{Black.400}" | no Figma path mapped for Supabase token color-filter-tag-border |
| component/color-mode/dark | tab.border.selected | "{Sky-blue.100}" | no Figma path mapped for Supabase token color-tab-border-selected |
| component/color-mode/dark | data.grid.default.header.text.color | "{Black.50}" | no Figma path mapped for Supabase token data-grid-default-header-text-color |
| component/color-mode/dark | tag.severity.undetermined.container.background.color | "{Stone.200}" | no Figma path mapped for Supabase token tag-severity-undetermined-container-background-color |
| component/color-mode/dark | time.picker.selected.list.border.color | "{Black.950}" | no Figma path mapped for Supabase token time-picker-selected-list-border-color |
| component/border-radius | file.upload.border.style | "{border.style.dashed}" | no Figma path mapped for Supabase token file-upload-border-style |
| component/border-radius | scrollbar.track.border.radius | "{size.6}" | no Figma path mapped for Supabase token scrollbar-track-border-radius |
| component/border-radius | width.modal.border | "{border.width.xs}" | no Figma path mapped for Supabase token width-modal-border |
| component/size | button.icon.width | "{size.36}" | no Figma path mapped for Supabase token button-icon-width |
| component/size | chat.default.transcribing.dot.height | "{size.4}" | no Figma path mapped for Supabase token chat-default-transcribing-dot-height |
| component/size | chat.default.transcribing.dot.width | "{size.4}" | no Figma path mapped for Supabase token chat-default-transcribing-dot-width |
| component/size | data.grid.header.row.cell.height | "{size.26}" | no Figma path mapped for Supabase token data-grid-header-row-cell-height |
| component/size | scrollbar.track.width | "{size.18}" | no Figma path mapped for Supabase token scrollbar-track-width |
| component/spacing | accordion.content.padding | "{spacing.11xl}" | no Figma path mapped for Supabase token accordion-content-padding |
| component/spacing | data.grid.inner.cell.spacing | "{spacing.negative.8xs}" | no Figma path mapped for Supabase token data-grid-inner-cell-spacing |
| component/spacing | dropdown.filter.margin.right | "{spacing.4xl}" | no Figma path mapped for Supabase token dropdown-filter-margin-right |
| component/spacing | toast.default.button.margin | "{spacing.5xs}" | no Figma path mapped for Supabase token toast-default-button-margin |

## Tokens in tokens/ missing from export (kept as-is) (0)

None.

## Exporter notes stripped from descriptions (217)

| set | token | note |
|---|---|---|
| primitive/color | Cyan.400 | override: value conflict: Figma wins -> fix Supabase (sheet row) |
| primitive/color | Yellow.100 | not in Supabase: add to Supabase as a new primitive value |
| primitive/color | Yellow.200 | not in Supabase: add to Supabase as a new primitive value |
| primitive/color | Forest-green.400 | not in Supabase: add to Supabase as a new primitive value |
| primitive/color | Indigo.300 | not in Supabase: add to Supabase as a new primitive value |
| primitive/color | Emerald.300 | not in Supabase: add to Supabase as a new primitive value |
| primitive/color | Teal.150 | alias of Supabase turquoise-150 |
| primitive/color | Teal.250 | alias of Supabase turquoise-250 |
| primitive/color | Teal.300 | not in Supabase: add to Supabase as a new primitive value |
| primitive/color | blue-rgba.50 | override: value conflict: Figma wins -> fix Supabase (sheet row) |
| primitive/color | sky-blue.rgba.50 | override: value conflict: Figma wins -> fix Supabase (sheet row) |
| primitive/color | Royal-blue | not in Supabase: add to Supabase as a new primitive value |
| primitive/color | Deep blue | not in Supabase: add to Supabase as a new primitive value |
| primitive/color | vivid blue | not in Supabase: add to Supabase as a new primitive value |
| primitive/color | soft cyan | not in Supabase: add to Supabase as a new primitive value |
| primitive/color | baby blue | not in Supabase: add to Supabase as a new primitive value |
| primitive/color | teal blue | not in Supabase: add to Supabase as a new primitive value |
| primitive/color | Ice blue | not in Supabase: add to Supabase as a new primitive value |
| primitive/color | Mint green | not in Supabase: add to Supabase as a new primitive value |
| primitive/color | Aquamarine | not in Supabase: add to Supabase as a new primitive value |
| primitive/color | Sand beige | not in Supabase: add to Supabase as a new primitive value |
| primitive/color | amber brown | not in Supabase: add to Supabase as a new primitive value |
| primitive/color | Golden yellow | not in Supabase: add to Supabase as a new primitive value |
| primitive/color | Copper rose | not in Supabase: add to Supabase as a new primitive value |
| primitive/color | Pale peach | not in Supabase: add to Supabase as a new primitive value |
| primitive/color | Crimson red | not in Supabase: add to Supabase as a new primitive value |
| primitive/color | Coral pink | not in Supabase: add to Supabase as a new primitive value |
| primitive/color | Magenta | not in Supabase: add to Supabase as a new primitive value |
| primitive/color | Electric purple | not in Supabase: add to Supabase as a new primitive value |
| primitive/color | Lavender | not in Supabase: add to Supabase as a new primitive value |
| primitive/color | Slate gray | not in Supabase: add to Supabase as a new primitive value |
| primitive/color | Graphite gray | not in Supabase: add to Supabase as a new primitive value |
| primitive/color | Cool gray | not in Supabase: add to Supabase as a new primitive value |
| primitive/color | Charcoal | not in Supabase: add to Supabase as a new primitive value |
| primitive/color | Warm gray | not in Supabase: add to Supabase as a new primitive value |
| primitive/color | black.850 | alias of Supabase black-850 |
| primitive/typography | line-height.xs | override: line-height: Supabase is unitless, Figma keeps rem; tiers xl-5xl are also offset by one (sheet: renumber tiers) |
| primitive/typography | line-height.sm | override: line-height: Supabase is unitless, Figma keeps rem; tiers xl-5xl are also offset by one (sheet: renumber tiers) |
| primitive/typography | line-height.md | override: line-height: Supabase is unitless, Figma keeps rem; tiers xl-5xl are also offset by one (sheet: renumber tiers) |
| primitive/typography | line-height.lg | override: line-height: Supabase is unitless, Figma keeps rem; tiers xl-5xl are also offset by one (sheet: renumber tiers) |
| primitive/typography | line-height.xl | override: line-height: Supabase is unitless, Figma keeps rem; tiers xl-5xl are also offset by one (sheet: renumber tiers) |
| primitive/typography | line-height.2xl | override: line-height: Supabase is unitless, Figma keeps rem; tiers xl-5xl are also offset by one (sheet: renumber tiers) |
| primitive/typography | line-height.3xl | override: line-height: Supabase is unitless, Figma keeps rem; tiers xl-5xl are also offset by one (sheet: renumber tiers) |
| primitive/typography | line-height.4xl | override: line-height: Supabase is unitless, Figma keeps rem; tiers xl-5xl are also offset by one (sheet: renumber tiers) |
| primitive/typography | line-height.5xl | override: line-height: Supabase is unitless, Figma keeps rem; tiers xl-5xl are also offset by one (sheet: renumber tiers) |
| semantic/color-mode/light | background.surface.row-active | alias of Supabase color-background-surface-row-selected |
| semantic/color-mode/light | background.status.success | alias of Supabase color-status-success |
| semantic/color-mode/light | background.status.error | alias of Supabase color-status-error |
| semantic/color-mode/light | background.status.informational | alias of Supabase color-status-informational |
| semantic/color-mode/light | background.status.warning | alias of Supabase color-status-warning |
| semantic/color-mode/light | text.tertiary | override: value conflict: Figma wins -> fix Supabase (sheet row) |
| semantic/color-mode/light | text.hover | alias of Supabase color-text-interactive-hover-primary |
| semantic/color-mode/light | text.interactive.secondary-hover | not in Supabase: add to Supabase as a new alias over primitive blue-gray-200 |
| semantic/color-mode/light | text.contrast.secondary | override: value conflict: Figma wins -> fix Supabase (sheet row) |
| semantic/color-mode/light | text.legend.disabled | alias of Supabase color-chart-disabled-legend-item |
| semantic/color-mode/light | text.table.header | alias of Supabase color-text-contrast-secondary |
| semantic/color-mode/light | border.divider | alias of Supabase color-background-input-list-item-hover-primary |
| semantic/color-mode/light | icon.active | override: value conflict: Figma wins -> fix Supabase (sheet row) |
| semantic/color-mode/dark | background.surface.row-active | alias of Supabase color-background-surface-row-selected |
| semantic/color-mode/dark | background.status.success | alias of Supabase color-status-success |
| semantic/color-mode/dark | background.status.error | alias of Supabase color-status-error |
| semantic/color-mode/dark | background.status.informational | alias of Supabase color-status-informational |
| semantic/color-mode/dark | background.status.warning | alias of Supabase color-status-warning |
| semantic/color-mode/dark | text.hover | alias of Supabase color-text-interactive-hover-primary |
| semantic/color-mode/dark | text.interactive.secondary-hover | not in Supabase: add to Supabase as a new alias over primitive blue-gray-200 |
| semantic/color-mode/dark | text.contrast.secondary | override: value conflict: Figma wins -> fix Supabase (sheet row) |
| semantic/color-mode/dark | text.legend.disabled | not in Supabase: add to Supabase as a new alias over primitive gray-400 |
| semantic/color-mode/dark | text.table.header | alias of Supabase color-text-contrast-secondary |
| semantic/color-mode/dark | border.surface.secondary | override: value conflict: Figma wins -> fix Supabase (sheet row) |
| semantic/color-mode/dark | border.divider | not in Supabase: add to Supabase as a new alias over primitive black-700 |
| semantic/size | size.width.full | override: Figma refs size.100 (100px) where Supabase has size-full (100%); looks like a Figma bug - confirm with Tina |
| semantic/size | size.height.full | override: Figma refs size.100 (100px) where Supabase has size-full (100%); looks like a Figma bug - confirm with Tina |
| semantic/border | radius.element.xs | not in Supabase: add to Supabase as a new alias over primitive border-radius-xs |
| semantic/border | border-width.outline.solid | override: token-bt ref is broken (no braces, borderWidth type, target does not exist); Supabase {border.style.solid} is the intended target - Tina to fix |
| semantic/spacing | spacing.element.padding.8xl | not in Supabase: add to Supabase as a new alias over primitive spacing-11xl |
| semantic/spacing | spacing.element.padding.3xl | alias of Supabase spacing-content-margin-3xl |
| semantic/typography | textCase.none | not in Supabase: text-case is not a Supabase concept; keep in Figma only |
| semantic/typography | text-decoration.none | override: Figma holds the literal, Supabase refs the primitive; same resolved value |
| semantic/typography | text-decoration.underline | override: Figma holds the literal, Supabase refs the primitive; same resolved value |
| semantic/typography | label.sm.secondary | override: typography composite differs on textDecoration (sheet: families) |
| semantic/typography | label.xs.default | override: typography composite differs on textDecoration (sheet: families) |
| semantic/typography | instructional.strong | override: typography composite differs on fontWeight (sheet: families) |
| semantic/typography | card.xs | override: typography composite differs on fontWeight (sheet: families) |
| semantic/typography | text.line-height.display.lg | override: line-height ladder: Supabase tier is one above Figma (sheet: renumber tiers) |
| semantic/typography | text.line-height.display.md | override: line-height ladder: Supabase tier is one above Figma (sheet: renumber tiers) |
| semantic/typography | text.line-height.heading.primary | override: line-height ladder: Supabase tier is one above Figma (sheet: renumber tiers) |
| semantic/typography | text.line-height.card.lg | override: line-height ladder: Supabase tier is one above Figma (sheet: renumber tiers) |
| semantic/typography | text.line-height.card.md | override: line-height ladder: Supabase tier is one above Figma (sheet: renumber tiers) |
| semantic/typography | text.line-height.card.sm | override: line-height ladder: Supabase tier is one above Figma (sheet: renumber tiers) |
| semantic/typography | text.line-height.card.xs | override: line-height ladder: Supabase tier is one above Figma (sheet: renumber tiers) |
| component/color-mode/light | button.secondary.icon.default.background.color | alias of Supabase color-background-interactive-secondary |
| component/color-mode/light | button.secondary.icon.hover.background.color | not in Supabase: add to Supabase as a new alias over primitive blue-gray-200 |
| component/color-mode/light | button.secondary.icon.active.background.color | not in Supabase: add to Supabase as a new alias over primitive blue-gray-300 |
| component/color-mode/light | button.danger.focus.background | not in Supabase: add to Supabase as a new alias over primitive orange-800 |
| component/color-mode/light | button.ghost.hover.label.color | alias of Supabase color-text-interactive-hover-secondary |
| component/color-mode/light | button.secondary-text.default.label.color | alias of Supabase color-text-interactive-secondary |
| component/color-mode/light | button.danger-icon.default.background | alias of Supabase color-background-interactive-transparent |
| component/color-mode/light | button.danger-icon.default.icon.color | alias of Supabase color-icon-error |
| component/color-mode/light | button.danger-icon.hover.background | not in Supabase: add to Supabase as a new alias over primitive rose-30 |
| component/color-mode/light | button.danger-icon.hover.icon.color | alias of Supabase color-icon-error |
| component/color-mode/light | button.danger-icon.focus.background | not in Supabase: add to Supabase as a new alias over primitive rose-30 |
| component/color-mode/light | button.danger-icon.focus.border.color | alias of Supabase color-border-outline-focus |
| component/color-mode/light | button.danger-icon.focus.icon.color | alias of Supabase color-icon-error |
| component/color-mode/light | button.danger-icon.active.background | not in Supabase: add to Supabase as a new alias over primitive rose-35 |
| component/color-mode/light | button.danger-icon.active.icon.color | alias of Supabase color-icon-error |
| component/color-mode/light | button.danger-icon.disabled.background | alias of Supabase color-background-interactive-transparent |
| component/color-mode/light | button.danger-icon.disabled.icon.color | alias of Supabase color-icon-error |
| component/color-mode/light | button.danger-text.active.background | not in Supabase: add to Supabase as a new alias over primitive rose-35 |
| component/color-mode/light | button.danger-text.hover.background | not in Supabase: add to Supabase as a new alias over primitive rose-30 |
| component/color-mode/light | button.danger-text.focus.background | not in Supabase: add to Supabase as a new alias over primitive rose-30 |
| component/color-mode/light | button.secondary-outline.default.label.color | alias of Supabase color-text-interactive-secondary |
| component/color-mode/light | button.secondary-outline.active.icon.color | not in Supabase: add to Supabase as a new alias over primitive blue-gray-300 |
| component/color-mode/light | data-grid.default.toolbar.selection.text.color | not in Supabase: add to Supabase as a new alias over primitive sky-blue-100 |
| component/color-mode/light | data-grid.default.toolbar.background.color | alias of Supabase color-background-layer-three |
| component/color-mode/light | data-grid.default.toolbar.row.background.color | alias of Supabase color-background-input-list-item-hover-primary |
| component/color-mode/light | data-grid.default.toolbar.border.color | alias of Supabase color-border-primary |
| component/color-mode/light | data-grid.default.toolbar.text.color | alias of Supabase color-text-contrast-tertiary |
| component/color-mode/light | data-grid.default.toolbar.input.background.color | alias of Supabase color-background-input |
| component/color-mode/light | data-grid.default.grid-cell.text.color | alias of Supabase color-text-contrast-primary |
| component/color-mode/light | slider.track.unselected.background.color | override: value conflict: Figma wins -> fix Supabase (sheet row) |
| component/color-mode/light | tag.severity.text.color | override: value conflict: Figma wins -> fix Supabase (sheet row) |
| component/color-mode/light | tag.color.1.prominent.fill | alias of Supabase color-severity-critical |
| component/color-mode/light | tag.color.1.subtle.fill | not in Supabase: add to Supabase as a new alias over primitive rose-25 |
| component/color-mode/light | tag.color.1.subtle.border | alias of Supabase color-border-error |
| component/color-mode/light | tag.color.2.prominent.fill | alias of Supabase color-severity-moderate |
| component/color-mode/light | tag.color.2.subtle.fill | not in Supabase: add to Supabase as a new alias over primitive orange-50 |
| component/color-mode/light | tag.color.2.subtle.border | not in Supabase: add to Supabase as a new alias over primitive peach-200 |
| component/color-mode/light | tag.color.2.subtle.text | not in Supabase: add to Supabase as a new alias over primitive peach-200 |
| component/color-mode/light | tag.color.3.prominent.fill | alias of Supabase color-severity-high |
| component/color-mode/light | tag.color.3.subtle.fill | not in Supabase: add to Supabase as a new alias over primitive gold-50 |
| component/color-mode/light | tag.color.3.subtle.border | not in Supabase: add to Supabase as a new alias over primitive gold-200 |
| component/color-mode/light | tag.color.3.subtle.text | not in Supabase: add to Supabase as a new alias over primitive gold-200 |
| component/color-mode/light | tag.color.4.prominent.fill | alias of Supabase color-status-success |
| component/color-mode/light | tag.color.4.subtle.fill | not in Supabase: add to Supabase as a new alias over primitive mint-50 |
| component/color-mode/light | tag.color.4.subtle.border | not in Supabase: add to Supabase as a new alias over primitive mint-300 |
| component/color-mode/light | tag.color.4.subtle.text | not in Supabase: add to Supabase as a new alias over primitive mint-300 |
| component/color-mode/light | tag.color.5.prominent.fill | not in Supabase: add to Supabase as a new alias over primitive turquoise-150 |
| component/color-mode/light | tag.color.5.subtle.fill | not in Supabase: add to Supabase as a new alias over primitive aqua-50 |
| component/color-mode/light | tag.color.5.subtle.border | not in Supabase: add to Supabase as a new alias over primitive aqua-300 |
| component/color-mode/light | tag.color.5.subtle.text | not in Supabase: add to Supabase as a new alias over primitive aqua-300 |
| component/color-mode/light | tag.color.6.prominent.fill | not in Supabase: add to Supabase as a new alias over primitive sky-blue-600 |
| component/color-mode/light | tag.color.6.subtle.fill | not in Supabase: add to Supabase as a new alias over primitive sky-blue-50 |
| component/color-mode/light | tag.color.6.subtle.border | alias of Supabase color-border-interactive-primary |
| component/color-mode/light | tag.color.6.subtle.text | alias of Supabase color-text-interactive-hover-secondary |
| component/color-mode/light | tag.color.undetermined.prominent.fill | not in Supabase: add to Supabase as a new alias over primitive stone-300 |
| component/color-mode/light | navigation.item.default.background.color | alias of Supabase color-background-layer-two |
| component/color-mode/light | navigation.item.hover.background.color | alias of Supabase color-background-input-list-item-hover-primary |
| component/color-mode/light | chat.default.ai-avatar.icon | alias of Supabase color-text-contrast-tertiary |
| component/color-mode/light | tile.hover.background.color | alias of Supabase color-background-layer-two |
| component/color-mode/dark | button.secondary.icon.hover.background.color | not in Supabase: add to Supabase as a new alias over primitive light-blue-200 |
| component/color-mode/dark | button.secondary.icon.active.background.color | not in Supabase: add to Supabase as a new alias over primitive light-blue-400 |
| component/color-mode/dark | button.secondary.icon.default.background.color | not in Supabase: add to Supabase as a new alias over primitive light-blue-200 |
| component/color-mode/dark | button.danger.focus.background | not in Supabase: add to Supabase as a new alias over primitive orange-800 |
| component/color-mode/dark | button.ghost.hover.label.color | alias of Supabase color-text-interactive-hover-primary |
| component/color-mode/dark | button.danger-icon.default.background | alias of Supabase color-background-interactive-transparent |
| component/color-mode/dark | button.danger-icon.default.icon.color | alias of Supabase color-icon-error |
| component/color-mode/dark | button.danger-icon.hover.background | not in Supabase: add to Supabase as a new alias over primitive rose-250 |
| component/color-mode/dark | button.danger-icon.hover.icon.color | alias of Supabase color-icon-error |
| component/color-mode/dark | button.danger-icon.focus.background | not in Supabase: add to Supabase as a new alias over primitive rose-250 |
| component/color-mode/dark | button.danger-icon.focus.border.color | alias of Supabase color-border-outline-focus |
| component/color-mode/dark | button.danger-icon.focus.icon.color | alias of Supabase color-icon-error |
| component/color-mode/dark | button.danger-icon.active.background | not in Supabase: add to Supabase as a new alias over primitive rose-275 |
| component/color-mode/dark | button.danger-icon.active.icon.color | alias of Supabase color-icon-error |
| component/color-mode/dark | button.danger-icon.disabled.background | alias of Supabase color-background-interactive-transparent |
| component/color-mode/dark | button.danger-icon.disabled.icon.color | alias of Supabase color-icon-error |
| component/color-mode/dark | button.danger-text.active.background | not in Supabase: add to Supabase as a new alias over primitive rose-275 |
| component/color-mode/dark | button.danger-text.hover.background | not in Supabase: add to Supabase as a new alias over primitive rose-250 |
| component/color-mode/dark | button.danger-text.focus.background | not in Supabase: add to Supabase as a new alias over primitive rose-250 |
| component/color-mode/dark | button.secondary-outline.default.label.color | alias of Supabase color-background-interactive-secondary |
| component/color-mode/dark | button.secondary-outline.active.icon.color | not in Supabase: add to Supabase as a new alias over primitive light-blue-400 |
| component/color-mode/dark | chart.stroke.color | override: value conflict: Figma wins -> fix Supabase (sheet row) |
| component/color-mode/dark | data-grid.default.toolbar.selection.text.color | alias of Supabase color-text-interactive-primary |
| component/color-mode/dark | data-grid.default.toolbar.background.color | alias of Supabase color-background-interactive-tertiary |
| component/color-mode/dark | data-grid.default.toolbar.row.background.color | alias of Supabase color-background-attention |
| component/color-mode/dark | data-grid.default.toolbar.border.color | alias of Supabase color-background-surface-row-hover |
| component/color-mode/dark | data-grid.default.toolbar.text.color | alias of Supabase color-text-primary |
| component/color-mode/dark | data-grid.default.toolbar.input.background.color | alias of Supabase color-background-input |
| component/color-mode/dark | data-grid.default.grid-cell.text.color | not in Supabase: add to Supabase as a new alias over primitive white |
| component/color-mode/dark | data-grid.text.color.color | alias of Supabase color-text-contrast-tertiary |
| component/color-mode/dark | data-grid.header.text.color | alias of Supabase color-text-contrast-tertiary |
| component/color-mode/dark | tag.color.1.prominent.fill | alias of Supabase color-severity-critical |
| component/color-mode/dark | tag.color.1.subtle.fill | not in Supabase: add to Supabase as a new alias over primitive rose-25 |
| component/color-mode/dark | tag.color.1.subtle.border | not in Supabase: add to Supabase as a new alias over primitive red-100 |
| component/color-mode/dark | tag.color.2.prominent.fill | alias of Supabase color-severity-moderate |
| component/color-mode/dark | tag.color.2.subtle.fill | not in Supabase: add to Supabase as a new alias over primitive orange-50 |
| component/color-mode/dark | tag.color.2.subtle.border | not in Supabase: add to Supabase as a new alias over primitive peach-200 |
| component/color-mode/dark | tag.color.2.subtle.text | not in Supabase: add to Supabase as a new alias over primitive peach-200 |
| component/color-mode/dark | tag.color.3.prominent.fill | alias of Supabase color-severity-high |
| component/color-mode/dark | tag.color.3.subtle.fill | not in Supabase: add to Supabase as a new alias over primitive gold-50 |
| component/color-mode/dark | tag.color.3.subtle.border | not in Supabase: add to Supabase as a new alias over primitive gold-200 |
| component/color-mode/dark | tag.color.3.subtle.text | not in Supabase: add to Supabase as a new alias over primitive gold-200 |
| component/color-mode/dark | tag.color.4.prominent.fill | alias of Supabase color-status-success |
| component/color-mode/dark | tag.color.4.subtle.fill | not in Supabase: add to Supabase as a new alias over primitive mint-50 |
| component/color-mode/dark | tag.color.4.subtle.border | not in Supabase: add to Supabase as a new alias over primitive mint-300 |
| component/color-mode/dark | tag.color.4.subtle.text | not in Supabase: add to Supabase as a new alias over primitive mint-300 |
| component/color-mode/dark | tag.color.5.prominent.fill | not in Supabase: add to Supabase as a new alias over primitive turquoise-250 |
| component/color-mode/dark | tag.color.5.subtle.fill | not in Supabase: add to Supabase as a new alias over primitive aqua-50 |
| component/color-mode/dark | tag.color.5.subtle.border | not in Supabase: add to Supabase as a new alias over primitive aqua-300 |
| component/color-mode/dark | tag.color.5.subtle.text | not in Supabase: add to Supabase as a new alias over primitive aqua-300 |
| component/color-mode/dark | tag.color.6.prominent.fill | not in Supabase: add to Supabase as a new alias over primitive sky-blue-500 |
| component/color-mode/dark | tag.color.6.subtle.fill | not in Supabase: add to Supabase as a new alias over primitive sky-blue-50 |
| component/color-mode/dark | tag.color.6.subtle.border | not in Supabase: add to Supabase as a new alias over primitive blue-100 |
| component/color-mode/dark | tag.color.6.subtle.text | not in Supabase: add to Supabase as a new alias over primitive blue-100 |
| component/color-mode/dark | tag.color.undetermined.prominent.fill | not in Supabase: add to Supabase as a new alias over primitive stone-300 |
| component/color-mode/dark | navigation.item.default.background.color | alias of Supabase color-background-interactive-tertiary |
| component/color-mode/dark | navigation.item.hover.background.color | alias of Supabase color-background-attention |
| component/color-mode/dark | chat.default.ai-avatar.icon | alias of Supabase color-text-contrast-primary |
| component/color-mode/dark | tile.hover.background.color | not in Supabase: add to Supabase as a new alias over primitive black-700 |
| component/border-radius | breadcrumb.focus.border-radius | alias of Supabase radius-element-2xs |
| component/border-radius | tag.default.container.radius | not in Supabase: add to Supabase as a new alias over primitive border-radius-lg |
| component/size | tab.container.height | alias of Supabase size-width-2xs |
| component/size | button.container.height.lg | not in Supabase: add to Supabase as a new alias over primitive size-40 |
| component/typography | chart.disabled.legend.item.text-decoration | override: Figma models this as a typography composite; Supabase holds only the text-decoration value |
| component/spacing | menu.default.menu-popup.margin | override: value conflict: Figma wins -> fix Supabase (sheet row) |
| component/spacing | slider.horizontal.margin | alias of Supabase spacing-element-gap-2xl |
| component/spacing | time-picker.text-button.gap | alias of Supabase spacing-element-padding-5xl |
| component/spacing | tooltip.content.gap | not in Supabase: add to Supabase as a new alias over primitive spacing-lg |

## Metadata the export dropped but tokens/ kept (17)

| set | token | keys kept |
|---|---|---|
| primitive/color | transparent | $extensions |
| primitive/color | Slate.rgba | $extensions |
| primitive/color | slate.rgba.08 | $extensions |
| primitive/opacity | opacity.26 | $extensions |
| primitive/opacity | opacity.50 | $extensions |
| component/color-mode/light | button.danger.active.background | color |
| component/color-mode/light | button.danger.hover.background | color |
| component/color-mode/light | button.danger-text.active.background | color |
| component/color-mode/light | button.danger-text.hover.background | color |
| component/color-mode/light | chat.default.reply.border | $extensions |
| component/color-mode/light | chat.default.typing-dot-1.background | $extensions |
| component/color-mode/dark | button.danger.active.background | color |
| component/color-mode/dark | button.danger.hover.background | color |
| component/color-mode/dark | button.danger-text.active.background | color |
| component/color-mode/dark | button.danger-text.hover.background | color |
| component/color-mode/dark | chat.default.reply.border | $extensions |
| component/color-mode/dark | chat.default.typing-dot-1.background | $extensions |

## Export sets with no counterpart in tokens/ (quarantined whole) (0)

None.

## Sets not present in export (unchanged) (0)

None.

