# DragAndDrop-CollectionView

With the release of iOS-11, Apple introduced Drag and Drop in UITableView and UICollection with a specialized API that works on the concept of Interactions (something like gestures). 

UITableView and UICollectionView have similar APIs to support Drag and Drop with some small differences. So, in this sample I'll be showing how you can integrate drag and drop in UICollectionView.

### This project provides Drag and Drop support in:
1. iPhone (In iPhone, Drag and Drop is supported only in the same app. In iPad, Drag and Drop is supported within multiple apps.)
2. iOS 11
3. Swift 4
4. UICollectionView

### Project Describes:
1. UICollectionViewDragDelegate and UICollectionViewDropDelegate to support Drag and Drop in UICollectionView.
2. Reordering cells in UICollectionView.
3. Controlling drag speed while reordering - reorderingCadence.
4. Copying data within multiple Collection Views.
5. Dragging and dropping single as well as multiple items.
6. What the element looks like when it is dragged around - Drag Preview.
7. How to handle drops i.e. copy/move/cancel/forbidden - Drop Proposal.
8. Performing actual drop in same/different UICollectionView.
 

## Preview
<img src="https://github.com/pgpt10/DragAndDrop-CollectionView/blob/master/DragDrop.gif"  width='300' height='534' alt="Preview gif">

## Project Details
The project describes Drag and Drop using 2 UICollectionViews and supports:
1. Reordering - Moving an element from source to destination indexpath within same Collection View.
2. Copying an element from 1st Collection View to 2nd CollectionView at a particular destination indexpath.
3. Forbidding the movement(copying/moving) of an element from 2nd Collection View to 1st CollectionView. 

## Implementation Details

#### <a href="https://medium.com/@p.gpt10/drag-it-drop-it-in-collection-table-ios-11-6bd28795b313">Here</a> you can find the complete implementation details of drag & drop in table view and collection view.
