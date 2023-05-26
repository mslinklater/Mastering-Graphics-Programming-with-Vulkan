# Raptor

3 layers. Dependencies go down.

* Application
* Graphics
* Foundation

All layers are contained in the 'raptor' namespace.

## Variable Naming

* All Vulkan resources are named vulkan_*
* Structures and classes are Capitalised
* Service derived classes are singletons
* Handles are simple indices in to resource pools
* Vulkan memory management is handled by the AMD Vulkan Memory Allocator (VMA)

## Application

## Graphics

## Foundation

**Array** (array.hpp) - vector class

**ArrayView** (array.hpp) - used in the profiler... a window over array contents ?

**BitMask** (bit.hpp) - helper for iterating through bits in a bitmask ?

**BitSet** (bit.hpp)

**BitSetFixed** (bit.hpp)

**BlobSerializer** (blob_serialization.hpp)

**Camera** (camera.hpp) - Fairly simple camera container

**Color** (color.hpp) - Simple u32 colour

**ResourcePool** (data_structures.hpp) - simple allocator for pooled resource types

**ResourcePoolTyped** (data_structures.hpp) - templated wrapper around ResourcePool
