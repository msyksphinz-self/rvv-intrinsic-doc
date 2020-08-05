<!--NOTE: This file is generated by rvv_intrinsic_gen.py-->

## Vector Mask Functions:

### [Vector Mask-Register Logical Functions](../rvv-intrinsic-api.md#161-vector-mask-register-logical-operations):

**Prototypes:**
``` C
vbool1_t vmand_mm_b1 (vbool1_t op1, vbool1_t op2);
vbool2_t vmand_mm_b2 (vbool2_t op1, vbool2_t op2);
vbool4_t vmand_mm_b4 (vbool4_t op1, vbool4_t op2);
vbool8_t vmand_mm_b8 (vbool8_t op1, vbool8_t op2);
vbool16_t vmand_mm_b16 (vbool16_t op1, vbool16_t op2);
vbool32_t vmand_mm_b32 (vbool32_t op1, vbool32_t op2);
vbool64_t vmand_mm_b64 (vbool64_t op1, vbool64_t op2);
vbool1_t vmnand_mm_b1 (vbool1_t op1, vbool1_t op2);
vbool2_t vmnand_mm_b2 (vbool2_t op1, vbool2_t op2);
vbool4_t vmnand_mm_b4 (vbool4_t op1, vbool4_t op2);
vbool8_t vmnand_mm_b8 (vbool8_t op1, vbool8_t op2);
vbool16_t vmnand_mm_b16 (vbool16_t op1, vbool16_t op2);
vbool32_t vmnand_mm_b32 (vbool32_t op1, vbool32_t op2);
vbool64_t vmnand_mm_b64 (vbool64_t op1, vbool64_t op2);
vbool1_t vmandnot_mm_b1 (vbool1_t op1, vbool1_t op2);
vbool2_t vmandnot_mm_b2 (vbool2_t op1, vbool2_t op2);
vbool4_t vmandnot_mm_b4 (vbool4_t op1, vbool4_t op2);
vbool8_t vmandnot_mm_b8 (vbool8_t op1, vbool8_t op2);
vbool16_t vmandnot_mm_b16 (vbool16_t op1, vbool16_t op2);
vbool32_t vmandnot_mm_b32 (vbool32_t op1, vbool32_t op2);
vbool64_t vmandnot_mm_b64 (vbool64_t op1, vbool64_t op2);
vbool1_t vmxor_mm_b1 (vbool1_t op1, vbool1_t op2);
vbool2_t vmxor_mm_b2 (vbool2_t op1, vbool2_t op2);
vbool4_t vmxor_mm_b4 (vbool4_t op1, vbool4_t op2);
vbool8_t vmxor_mm_b8 (vbool8_t op1, vbool8_t op2);
vbool16_t vmxor_mm_b16 (vbool16_t op1, vbool16_t op2);
vbool32_t vmxor_mm_b32 (vbool32_t op1, vbool32_t op2);
vbool64_t vmxor_mm_b64 (vbool64_t op1, vbool64_t op2);
vbool1_t vmor_mm_b1 (vbool1_t op1, vbool1_t op2);
vbool2_t vmor_mm_b2 (vbool2_t op1, vbool2_t op2);
vbool4_t vmor_mm_b4 (vbool4_t op1, vbool4_t op2);
vbool8_t vmor_mm_b8 (vbool8_t op1, vbool8_t op2);
vbool16_t vmor_mm_b16 (vbool16_t op1, vbool16_t op2);
vbool32_t vmor_mm_b32 (vbool32_t op1, vbool32_t op2);
vbool64_t vmor_mm_b64 (vbool64_t op1, vbool64_t op2);
vbool1_t vmnor_mm_b1 (vbool1_t op1, vbool1_t op2);
vbool2_t vmnor_mm_b2 (vbool2_t op1, vbool2_t op2);
vbool4_t vmnor_mm_b4 (vbool4_t op1, vbool4_t op2);
vbool8_t vmnor_mm_b8 (vbool8_t op1, vbool8_t op2);
vbool16_t vmnor_mm_b16 (vbool16_t op1, vbool16_t op2);
vbool32_t vmnor_mm_b32 (vbool32_t op1, vbool32_t op2);
vbool64_t vmnor_mm_b64 (vbool64_t op1, vbool64_t op2);
vbool1_t vmornot_mm_b1 (vbool1_t op1, vbool1_t op2);
vbool2_t vmornot_mm_b2 (vbool2_t op1, vbool2_t op2);
vbool4_t vmornot_mm_b4 (vbool4_t op1, vbool4_t op2);
vbool8_t vmornot_mm_b8 (vbool8_t op1, vbool8_t op2);
vbool16_t vmornot_mm_b16 (vbool16_t op1, vbool16_t op2);
vbool32_t vmornot_mm_b32 (vbool32_t op1, vbool32_t op2);
vbool64_t vmornot_mm_b64 (vbool64_t op1, vbool64_t op2);
vbool1_t vmxnor_mm_b1 (vbool1_t op1, vbool1_t op2);
vbool2_t vmxnor_mm_b2 (vbool2_t op1, vbool2_t op2);
vbool4_t vmxnor_mm_b4 (vbool4_t op1, vbool4_t op2);
vbool8_t vmxnor_mm_b8 (vbool8_t op1, vbool8_t op2);
vbool16_t vmxnor_mm_b16 (vbool16_t op1, vbool16_t op2);
vbool32_t vmxnor_mm_b32 (vbool32_t op1, vbool32_t op2);
vbool64_t vmxnor_mm_b64 (vbool64_t op1, vbool64_t op2);
vbool1_t vmmv_m_b1 (vbool1_t op1);
vbool2_t vmmv_m_b2 (vbool2_t op1);
vbool4_t vmmv_m_b4 (vbool4_t op1);
vbool8_t vmmv_m_b8 (vbool8_t op1);
vbool16_t vmmv_m_b16 (vbool16_t op1);
vbool32_t vmmv_m_b32 (vbool32_t op1);
vbool64_t vmmv_m_b64 (vbool64_t op1);
vbool1_t vmclr_m_b1 ();
vbool2_t vmclr_m_b2 ();
vbool4_t vmclr_m_b4 ();
vbool8_t vmclr_m_b8 ();
vbool16_t vmclr_m_b16 ();
vbool32_t vmclr_m_b32 ();
vbool64_t vmclr_m_b64 ();
vbool1_t vmset_m_b1 ();
vbool2_t vmset_m_b2 ();
vbool4_t vmset_m_b4 ();
vbool8_t vmset_m_b8 ();
vbool16_t vmset_m_b16 ();
vbool32_t vmset_m_b32 ();
vbool64_t vmset_m_b64 ();
vbool1_t vmnot_m_b1 (vbool1_t op1);
vbool2_t vmnot_m_b2 (vbool2_t op1);
vbool4_t vmnot_m_b4 (vbool4_t op1);
vbool8_t vmnot_m_b8 (vbool8_t op1);
vbool16_t vmnot_m_b16 (vbool16_t op1);
vbool32_t vmnot_m_b32 (vbool32_t op1);
vbool64_t vmnot_m_b64 (vbool64_t op1);
```
### [Vector mask population count Functions](../rvv-intrinsic-api.md#162-vector-mask-population-count-vpopc):

**Prototypes:**
``` C
unsigned long vpopc_m_b1 (vbool1_t op1);
unsigned long vpopc_m_b2 (vbool2_t op1);
unsigned long vpopc_m_b4 (vbool4_t op1);
unsigned long vpopc_m_b8 (vbool8_t op1);
unsigned long vpopc_m_b16 (vbool16_t op1);
unsigned long vpopc_m_b32 (vbool32_t op1);
unsigned long vpopc_m_b64 (vbool64_t op1);
// masked functions
unsigned long vpopc_m_b1_m (vbool1_t mask, vbool1_t op1);
unsigned long vpopc_m_b2_m (vbool2_t mask, vbool2_t op1);
unsigned long vpopc_m_b4_m (vbool4_t mask, vbool4_t op1);
unsigned long vpopc_m_b8_m (vbool8_t mask, vbool8_t op1);
unsigned long vpopc_m_b16_m (vbool16_t mask, vbool16_t op1);
unsigned long vpopc_m_b32_m (vbool32_t mask, vbool32_t op1);
unsigned long vpopc_m_b64_m (vbool64_t mask, vbool64_t op1);
```
### [Find-first-set mask bit Functions](../rvv-intrinsic-api.md#163-vfirst-find-first-set-mask-bit):

**Prototypes:**
``` C
long vfirst_m_b1 (vbool1_t op1);
long vfirst_m_b2 (vbool2_t op1);
long vfirst_m_b4 (vbool4_t op1);
long vfirst_m_b8 (vbool8_t op1);
long vfirst_m_b16 (vbool16_t op1);
long vfirst_m_b32 (vbool32_t op1);
long vfirst_m_b64 (vbool64_t op1);
// masked functions
long vfirst_m_b1_m (vbool1_t mask, vbool1_t op1);
long vfirst_m_b2_m (vbool2_t mask, vbool2_t op1);
long vfirst_m_b4_m (vbool4_t mask, vbool4_t op1);
long vfirst_m_b8_m (vbool8_t mask, vbool8_t op1);
long vfirst_m_b16_m (vbool16_t mask, vbool16_t op1);
long vfirst_m_b32_m (vbool32_t mask, vbool32_t op1);
long vfirst_m_b64_m (vbool64_t mask, vbool64_t op1);
```
### [Set-before-first mask bit Functions](../rvv-intrinsic-api.md#164-vmsbfm-set-before-first-mask-bit):

**Prototypes:**
``` C
vbool1_t vmsbf_m_b1 (vbool1_t op1);
vbool2_t vmsbf_m_b2 (vbool2_t op1);
vbool4_t vmsbf_m_b4 (vbool4_t op1);
vbool8_t vmsbf_m_b8 (vbool8_t op1);
vbool16_t vmsbf_m_b16 (vbool16_t op1);
vbool32_t vmsbf_m_b32 (vbool32_t op1);
vbool64_t vmsbf_m_b64 (vbool64_t op1);
// masked functions
vbool1_t vmsbf_m_b1_m (vbool1_t mask, vbool1_t maskedoff, vbool1_t op1);
vbool2_t vmsbf_m_b2_m (vbool2_t mask, vbool2_t maskedoff, vbool2_t op1);
vbool4_t vmsbf_m_b4_m (vbool4_t mask, vbool4_t maskedoff, vbool4_t op1);
vbool8_t vmsbf_m_b8_m (vbool8_t mask, vbool8_t maskedoff, vbool8_t op1);
vbool16_t vmsbf_m_b16_m (vbool16_t mask, vbool16_t maskedoff, vbool16_t op1);
vbool32_t vmsbf_m_b32_m (vbool32_t mask, vbool32_t maskedoff, vbool32_t op1);
vbool64_t vmsbf_m_b64_m (vbool64_t mask, vbool64_t maskedoff, vbool64_t op1);
```
### [Set-including-first mask bit Functions](../rvv-intrinsic-api.md#165-vmsifm-set-including-first-mask-bit):

**Prototypes:**
``` C
vbool1_t vmsif_m_b1 (vbool1_t op1);
vbool2_t vmsif_m_b2 (vbool2_t op1);
vbool4_t vmsif_m_b4 (vbool4_t op1);
vbool8_t vmsif_m_b8 (vbool8_t op1);
vbool16_t vmsif_m_b16 (vbool16_t op1);
vbool32_t vmsif_m_b32 (vbool32_t op1);
vbool64_t vmsif_m_b64 (vbool64_t op1);
// masked functions
vbool1_t vmsif_m_b1_m (vbool1_t mask, vbool1_t maskedoff, vbool1_t op1);
vbool2_t vmsif_m_b2_m (vbool2_t mask, vbool2_t maskedoff, vbool2_t op1);
vbool4_t vmsif_m_b4_m (vbool4_t mask, vbool4_t maskedoff, vbool4_t op1);
vbool8_t vmsif_m_b8_m (vbool8_t mask, vbool8_t maskedoff, vbool8_t op1);
vbool16_t vmsif_m_b16_m (vbool16_t mask, vbool16_t maskedoff, vbool16_t op1);
vbool32_t vmsif_m_b32_m (vbool32_t mask, vbool32_t maskedoff, vbool32_t op1);
vbool64_t vmsif_m_b64_m (vbool64_t mask, vbool64_t maskedoff, vbool64_t op1);
```
### [Set-only-first mask bit Functions](../rvv-intrinsic-api.md#166-vmsofm-set-only-first-mask-bit):

**Prototypes:**
``` C
vbool1_t vmsof_m_b1 (vbool1_t op1);
vbool2_t vmsof_m_b2 (vbool2_t op1);
vbool4_t vmsof_m_b4 (vbool4_t op1);
vbool8_t vmsof_m_b8 (vbool8_t op1);
vbool16_t vmsof_m_b16 (vbool16_t op1);
vbool32_t vmsof_m_b32 (vbool32_t op1);
vbool64_t vmsof_m_b64 (vbool64_t op1);
// masked functions
vbool1_t vmsof_m_b1_m (vbool1_t mask, vbool1_t maskedoff, vbool1_t op1);
vbool2_t vmsof_m_b2_m (vbool2_t mask, vbool2_t maskedoff, vbool2_t op1);
vbool4_t vmsof_m_b4_m (vbool4_t mask, vbool4_t maskedoff, vbool4_t op1);
vbool8_t vmsof_m_b8_m (vbool8_t mask, vbool8_t maskedoff, vbool8_t op1);
vbool16_t vmsof_m_b16_m (vbool16_t mask, vbool16_t maskedoff, vbool16_t op1);
vbool32_t vmsof_m_b32_m (vbool32_t mask, vbool32_t maskedoff, vbool32_t op1);
vbool64_t vmsof_m_b64_m (vbool64_t mask, vbool64_t maskedoff, vbool64_t op1);
```
### [Vector Iota Functions](../rvv-intrinsic-api.md#168-vector-iota-operations):

**Prototypes:**
``` C
vuint8mf8_t viota_m_u8mf8_vl (vbool64_t op1, size_t vl);
vuint8mf4_t viota_m_u8mf4_vl (vbool32_t op1, size_t vl);
vuint8mf2_t viota_m_u8mf2_vl (vbool16_t op1, size_t vl);
vuint8m1_t viota_m_u8m1_vl (vbool8_t op1, size_t vl);
vuint8m2_t viota_m_u8m2_vl (vbool4_t op1, size_t vl);
vuint8m4_t viota_m_u8m4_vl (vbool2_t op1, size_t vl);
vuint8m8_t viota_m_u8m8_vl (vbool1_t op1, size_t vl);
vuint16mf4_t viota_m_u16mf4_vl (vbool64_t op1, size_t vl);
vuint16mf2_t viota_m_u16mf2_vl (vbool32_t op1, size_t vl);
vuint16m1_t viota_m_u16m1_vl (vbool16_t op1, size_t vl);
vuint16m2_t viota_m_u16m2_vl (vbool8_t op1, size_t vl);
vuint16m4_t viota_m_u16m4_vl (vbool4_t op1, size_t vl);
vuint16m8_t viota_m_u16m8_vl (vbool2_t op1, size_t vl);
vuint32mf2_t viota_m_u32mf2_vl (vbool64_t op1, size_t vl);
vuint32m1_t viota_m_u32m1_vl (vbool32_t op1, size_t vl);
vuint32m2_t viota_m_u32m2_vl (vbool16_t op1, size_t vl);
vuint32m4_t viota_m_u32m4_vl (vbool8_t op1, size_t vl);
vuint32m8_t viota_m_u32m8_vl (vbool4_t op1, size_t vl);
vuint64m1_t viota_m_u64m1_vl (vbool64_t op1, size_t vl);
vuint64m2_t viota_m_u64m2_vl (vbool32_t op1, size_t vl);
vuint64m4_t viota_m_u64m4_vl (vbool16_t op1, size_t vl);
vuint64m8_t viota_m_u64m8_vl (vbool8_t op1, size_t vl);
// masked functions
vuint8mf8_t viota_m_u8mf8_m_vl (vbool64_t mask, vuint8mf8_t maskedoff, vbool64_t op1, size_t vl);
vuint8mf4_t viota_m_u8mf4_m_vl (vbool32_t mask, vuint8mf4_t maskedoff, vbool32_t op1, size_t vl);
vuint8mf2_t viota_m_u8mf2_m_vl (vbool16_t mask, vuint8mf2_t maskedoff, vbool16_t op1, size_t vl);
vuint8m1_t viota_m_u8m1_m_vl (vbool8_t mask, vuint8m1_t maskedoff, vbool8_t op1, size_t vl);
vuint8m2_t viota_m_u8m2_m_vl (vbool4_t mask, vuint8m2_t maskedoff, vbool4_t op1, size_t vl);
vuint8m4_t viota_m_u8m4_m_vl (vbool2_t mask, vuint8m4_t maskedoff, vbool2_t op1, size_t vl);
vuint8m8_t viota_m_u8m8_m_vl (vbool1_t mask, vuint8m8_t maskedoff, vbool1_t op1, size_t vl);
vuint16mf4_t viota_m_u16mf4_m_vl (vbool64_t mask, vuint16mf4_t maskedoff, vbool64_t op1, size_t vl);
vuint16mf2_t viota_m_u16mf2_m_vl (vbool32_t mask, vuint16mf2_t maskedoff, vbool32_t op1, size_t vl);
vuint16m1_t viota_m_u16m1_m_vl (vbool16_t mask, vuint16m1_t maskedoff, vbool16_t op1, size_t vl);
vuint16m2_t viota_m_u16m2_m_vl (vbool8_t mask, vuint16m2_t maskedoff, vbool8_t op1, size_t vl);
vuint16m4_t viota_m_u16m4_m_vl (vbool4_t mask, vuint16m4_t maskedoff, vbool4_t op1, size_t vl);
vuint16m8_t viota_m_u16m8_m_vl (vbool2_t mask, vuint16m8_t maskedoff, vbool2_t op1, size_t vl);
vuint32mf2_t viota_m_u32mf2_m_vl (vbool64_t mask, vuint32mf2_t maskedoff, vbool64_t op1, size_t vl);
vuint32m1_t viota_m_u32m1_m_vl (vbool32_t mask, vuint32m1_t maskedoff, vbool32_t op1, size_t vl);
vuint32m2_t viota_m_u32m2_m_vl (vbool16_t mask, vuint32m2_t maskedoff, vbool16_t op1, size_t vl);
vuint32m4_t viota_m_u32m4_m_vl (vbool8_t mask, vuint32m4_t maskedoff, vbool8_t op1, size_t vl);
vuint32m8_t viota_m_u32m8_m_vl (vbool4_t mask, vuint32m8_t maskedoff, vbool4_t op1, size_t vl);
vuint64m1_t viota_m_u64m1_m_vl (vbool64_t mask, vuint64m1_t maskedoff, vbool64_t op1, size_t vl);
vuint64m2_t viota_m_u64m2_m_vl (vbool32_t mask, vuint64m2_t maskedoff, vbool32_t op1, size_t vl);
vuint64m4_t viota_m_u64m4_m_vl (vbool16_t mask, vuint64m4_t maskedoff, vbool16_t op1, size_t vl);
vuint64m8_t viota_m_u64m8_m_vl (vbool8_t mask, vuint64m8_t maskedoff, vbool8_t op1, size_t vl);
```
### [Vector Element Index Functions](../rvv-intrinsic-api.md#169-vector-element-index-operations):

**Prototypes:**
``` C
vuint8mf8_t vid_v_u8mf8_vl (size_t vl);
vuint8mf4_t vid_v_u8mf4_vl (size_t vl);
vuint8mf2_t vid_v_u8mf2_vl (size_t vl);
vuint8m1_t vid_v_u8m1_vl (size_t vl);
vuint8m2_t vid_v_u8m2_vl (size_t vl);
vuint8m4_t vid_v_u8m4_vl (size_t vl);
vuint8m8_t vid_v_u8m8_vl (size_t vl);
vuint16mf4_t vid_v_u16mf4_vl (size_t vl);
vuint16mf2_t vid_v_u16mf2_vl (size_t vl);
vuint16m1_t vid_v_u16m1_vl (size_t vl);
vuint16m2_t vid_v_u16m2_vl (size_t vl);
vuint16m4_t vid_v_u16m4_vl (size_t vl);
vuint16m8_t vid_v_u16m8_vl (size_t vl);
vuint32mf2_t vid_v_u32mf2_vl (size_t vl);
vuint32m1_t vid_v_u32m1_vl (size_t vl);
vuint32m2_t vid_v_u32m2_vl (size_t vl);
vuint32m4_t vid_v_u32m4_vl (size_t vl);
vuint32m8_t vid_v_u32m8_vl (size_t vl);
vuint64m1_t vid_v_u64m1_vl (size_t vl);
vuint64m2_t vid_v_u64m2_vl (size_t vl);
vuint64m4_t vid_v_u64m4_vl (size_t vl);
vuint64m8_t vid_v_u64m8_vl (size_t vl);
// masked functions
vuint8mf8_t vid_v_u8mf8_m_vl (vbool64_t mask, vuint8mf8_t maskedoff, size_t vl);
vuint8mf4_t vid_v_u8mf4_m_vl (vbool32_t mask, vuint8mf4_t maskedoff, size_t vl);
vuint8mf2_t vid_v_u8mf2_m_vl (vbool16_t mask, vuint8mf2_t maskedoff, size_t vl);
vuint8m1_t vid_v_u8m1_m_vl (vbool8_t mask, vuint8m1_t maskedoff, size_t vl);
vuint8m2_t vid_v_u8m2_m_vl (vbool4_t mask, vuint8m2_t maskedoff, size_t vl);
vuint8m4_t vid_v_u8m4_m_vl (vbool2_t mask, vuint8m4_t maskedoff, size_t vl);
vuint8m8_t vid_v_u8m8_m_vl (vbool1_t mask, vuint8m8_t maskedoff, size_t vl);
vuint16mf4_t vid_v_u16mf4_m_vl (vbool64_t mask, vuint16mf4_t maskedoff, size_t vl);
vuint16mf2_t vid_v_u16mf2_m_vl (vbool32_t mask, vuint16mf2_t maskedoff, size_t vl);
vuint16m1_t vid_v_u16m1_m_vl (vbool16_t mask, vuint16m1_t maskedoff, size_t vl);
vuint16m2_t vid_v_u16m2_m_vl (vbool8_t mask, vuint16m2_t maskedoff, size_t vl);
vuint16m4_t vid_v_u16m4_m_vl (vbool4_t mask, vuint16m4_t maskedoff, size_t vl);
vuint16m8_t vid_v_u16m8_m_vl (vbool2_t mask, vuint16m8_t maskedoff, size_t vl);
vuint32mf2_t vid_v_u32mf2_m_vl (vbool64_t mask, vuint32mf2_t maskedoff, size_t vl);
vuint32m1_t vid_v_u32m1_m_vl (vbool32_t mask, vuint32m1_t maskedoff, size_t vl);
vuint32m2_t vid_v_u32m2_m_vl (vbool16_t mask, vuint32m2_t maskedoff, size_t vl);
vuint32m4_t vid_v_u32m4_m_vl (vbool8_t mask, vuint32m4_t maskedoff, size_t vl);
vuint32m8_t vid_v_u32m8_m_vl (vbool4_t mask, vuint32m8_t maskedoff, size_t vl);
vuint64m1_t vid_v_u64m1_m_vl (vbool64_t mask, vuint64m1_t maskedoff, size_t vl);
vuint64m2_t vid_v_u64m2_m_vl (vbool32_t mask, vuint64m2_t maskedoff, size_t vl);
vuint64m4_t vid_v_u64m4_m_vl (vbool16_t mask, vuint64m4_t maskedoff, size_t vl);
vuint64m8_t vid_v_u64m8_m_vl (vbool8_t mask, vuint64m8_t maskedoff, size_t vl);
```